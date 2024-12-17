## Introduction

One of the most recognizable and successful media franchises of all time, the Pokémon videogames are known for their upbeat settings, colorful Pokémon designs, and accessible gameplay that can appeal to an incredibly wide audience. However, beyond its deceptively simple appearance lies an incredibly complex battle system with a wealth of intricacies that allow the player countless opportunities to outmaneuver and defeat their opponents. As a longtime competitive Pokemon player, my final project will aim to develop a predictive model that can accurately determine how viable a Pokemon is in top-level competitive play based on its basic attributes.

While the “official” ruleset used in Nintendo-sanctioned tournaments uses a ‘doubles’ format, I have instead chosen to judge a Pokemon’s viability in singles. The most commonly accepted, albeit unofficial, singles Pokemon formats are run by [Smogon](https://www.smogon.com/), a forum that also owns [Pokemon Showdown](https://www.PokemonShowdown.com/), an incredibly popular open-source online Pokemon battle simulator.

Smogon uses a tiered system to separate Pokemon based on usage– any Pokemon that doesn’t see at least a 5% usage rate in one tier becomes eligible for use in the next tier down, and so on. There is also a ‘banlist’ for Pokemon that are deemed to be too strong in one tier despite not meeting the usage requirements in the tier above. From weakest to strongest, the tiers are ZU (no abbreviation), ZUBanList (ZUBL), NeverUsed (NU), NUBanList (NUBL), RarelyUsed (RU), RUBL, UnderUsed (UU), UUBL, OverUsed, Ubers (the OU banlist), and AnythingGoes (special circumstances, only used twice in history).

Compared to the official rules where the list of allowed Pokemon is changed regularly, Smogon’s rules are much more stable; every Pokemon will always be playable in at least one of the tiers. Smogon’s multi-tiered system also allows for the analysis of a much larger range of Pokemon– if we tried to measure viability from just a Pokemon’s usage rate, there are only ever a few dozen usable Pokemon at a time in doubles.

My predictive models will be using a Pokemon’s gameplay statistics (base stats, typing, etc.) to attempt to guess which its viability tier in Smogon singles.

#### IMPORTANT:
Apart from this readme, all of my work for this project is contained in the 5 notebooks, labeled from a-d. All other files are unneccesary to run the project, as they are downloaded and/or created as a result of the code run from the notebooks.
