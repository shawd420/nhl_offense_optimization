# nhl_offense_optimization
Leveraging shot location data to optimize offensive line combinations


### How to run the project
Due to the extensive data mining in this project, some files are dedicated to mining and must be run prior to begining analysis. To mimick the results, notebooks must be run in the following order:

1. **miner.ipynb** or **input/pkl_to_txt.ipynb**  -  The first file will mine all events from the 2019-20 season and will take approximately 10 minutes to complete. To save time, running the second file begining at cell 6 will unzip a compressed version of the mined data and make it usable for analysis
2. **shot_map.ipynb**  -  This file generates line maps for a given combination of n players
3. **line_combination_miner.ipynb**  -  This file mines daily line combinations from www.dailyfaceoff.com
4. **line_combination_stats.ipynb**  -  This file tabulates stats for all line combinations mined. Also, generates scatter plots and explores relationships between features


### Other programs
The files **stat_counter.ipynb** and **shot_precision.ipynb** serve the purpose of a proof of concept. They were first attempts at shaping the data and creating visuals but they are not required to recreate the project.


### My article summarizing findings
An article explaining my findings can be found at my [website](http://bardownstats.org/efficient-line-hypothesis/).
