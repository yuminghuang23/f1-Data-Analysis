# f1-Data-Analysis

### To execute the scripts:
Consists 2 .ipynb scripts in folder 'scripts'

1. Run 'Explore & Cleaning.ipynb' first to pick up data files from 'DataAnalystAssignment' <br>
        - cleaned data is stored in 'WrangledDatasets'
2. Run 'Tasks Analysis.ipynb' to analysis on the data <br>
        - output data is stored in 'Result/ResultDatasets' <br>
        - graphs are stored in 'Result/Graph'
3. Analysis Report can be found in 'Result/', name: 'Report.pdf'

### Directory Tree
```
|   requirements.txt   
+---DataAnalystAssignment
|       .DS_Store
|       circuits.csv
|       constructors.csv
|       constructor_standings.csv
|       Data Analyst Assignment.pdf
|       drivers.csv
|       driverStandings.csv
|       driver_standings.csv
|       lapTimes.csv
|       pitStops.csv
|       races.csv
|       results.csv
|       status.csv
|       
+---Result
|   |   Report.pdf
|   |   
|   +---Graph
|   |       Constructor Championship Win Rate from 1950 vs from 1958.png
|   |       Constructor Championship Win Rate from 1958.png
|   |       Constructor Championship Wins Count from 1950 vs from 1958.png
|   |       Constructor Championship Wins Count from 1958.png
|   |       Fastest Lap Time Per Track.png
|   |       Top 10 Driver Race Place Count.png
|   |       Top 10 Driver Race Win Rate.png
|   |       Top 20 Dangerous Track by Accidents and Collision Tier1.png
|   |       Top 20 Dangerous Track by Accidents and Collision Tier2.png
|   |       
|   \---ResultDatasets
|           constructor_win_1958plus.csv
|           constructor_win_alltime.csv
|           dangerous_tracks_tier1.csv
|           dangerous_tracks_tier2.csv
|           driver_wins.csv
|           driver_wins_slimed.csv
|           fastest_tracks.csv
|           
+---scripts
|      Explore & Cleaning.ipynb
|      Tasks Analysis.ipynb
|   
|           
\---WrangledDatasets
        results_wrangled.csv
```

## Requirments to run locally
1. requires Python 3 or higher <br>
        (can be found here: https://www.python.org/downloads/windows/)
2. requires installation of Jupyter Notebook or Jupter Lab, either will do<br>
        (refer to official site for installation: https://jupyter.org/install)
3. required libraries are in 'requirements.txt', can be installed using:
```
pip3 install -r /path/to/requirements.txt
```
## Requirments to on cloud
1. use Binder: https://mybinder.org/
2. copy this repo's link: https://github.com/yuminghuang23/f1-Data-Analysis and paste into Binder <br>
   (refer to this document for more information: https://mybinder.readthedocs.io/en/latest/introduction.html)
3. Click 'Launch' and Binder will auto build image and deploy

Or, try the already deployed version: https://gesis.mybinder.org/binder/v2/gh/yuminghuang23/f1-Data-Analysis/583414e209b7d354d01a7fcb45068dd1f12cf50b


