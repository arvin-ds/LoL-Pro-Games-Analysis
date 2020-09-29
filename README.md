# LoL-Pro-Games-Analysis
## Summary
In this project, I use [OracleElixir's League of Legends Pro game data](https://oracleselixir.com/) for 2020 to analyze the statistics of winning and losing teams. I choose certain end-game datapoints as features (listed below) that I normalize, correlate, and model to predict team victory. 

The library I use in this is sklearn - this is my first project in Machine Learning and I am beyond excited about venturing into this feild.

## Features
I chose these features beginning with the word 'first'. These are all in-game objectives that are thought to correlate highly with victory.

+ firstdragon
+ firstherald
+ firstbaron
+ firsttower
+ firstmidtower
+ firsttothreetowers

## Conclusion
### 1. We see that Blue Team wins more often.


*"What does this mean?"*

It could mean anything... It could mean that blue side of the map is better for player performance, or could just be by chance that blue teams won more often in our dataset.

Further analysis is required to come to a conclusion about this.

### 2. We get about a ~85% accuracy in prediction by our models.


*"What does this mean?"*

This means that our models correctly predict that the above end-game objectives correlate with victory in about 85% of the of the total number of cases tested.

*"Isn't that low?"*

Maybe, in some cases - __but not here__

Here, we are analying PROFESSIONAL games, and not random solo queue games. We would expect that professional players have skillsets that allow them to win beyond the aforementioned given end-game objectives.

Our model accuracy is exactly as was expected.
