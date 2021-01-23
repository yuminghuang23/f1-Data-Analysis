# f1-Data-Analysis

### To execute the scripts:
Consists 2 .ipynb scripts in folder 'scripts'

1. Run 'Explore & Cleaning.ipynb' first to pick up data files from 'DataAnalystAssignment'
        - cleaned data is stored in 'WrangledDatasets'
2. Run 'Tasks Analysis.ipynb' to analysis on the data
        - output data is stored in 'Result/ResultDatasets'
        - graphs are stored in 'Result/Graph'
3. Repot on the analysis can be found in 'Result/', name: 'Report.pdf'

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
1. requires installation of Jupyter Notebook
2. required libraries are in 'requirements.txt' using
```
pip install -r /path/to/requirements.txt
```
## Requirments to on cloud
1. use Binder: https://mybinder.org/
2. copy this repo's link: https://github.com/yuminghuang23/f1-Data-Analysis and paste into Binder 
   (refer to this document for more information: https://mybinder.readthedocs.io/en/latest/introduction.html)
3. Click 'Launch' and Binder will auto build image and deploy



