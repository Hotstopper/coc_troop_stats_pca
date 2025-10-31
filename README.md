# coc_troop_stats_pca

## Data
I collected Clash of Clans troop statistics from [https://clashofclans.fandom.com/](url). I took the statistics of each troop for their maximum level as of August 2024, and put them into Troop_stats.csv

The statistics of interest are:
1. Housing space
2. Movement speed
3. Attack speed (in hertz)
4. Range (tiles)
5. Damage radius (tiles)
6. Damage per attack
7. Hitpoints
8. Ability to attack air (1 if yes, 0 if no)

The statistics are designed such that the higher the number, the stronger the troop.

## PCA
I then applied PCA, selected the first two principal components, and plotted them on a 2D graph.
The code can be found in troop.ipynb
The plotted results can be found in coc_pca.png
