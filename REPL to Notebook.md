### Cell in a notebook
- In []: >
- Cell -> Run Cells
- shift + enter to run a cell
- tab to autocomplete
- execute a cell so autocomplete works in other cells
- shift + tab with cursor on a command shows signature of the command

### Managing multiple cells
- Cells -> runall
- Cells -> runallbelow

## Shell commands
- called magic commands starts with a bang or exclamation 
- > !pwd
- > !dir
- > !ls - l
- access the In [] in a command 
- > In [11]
- > Out [11]
- _ is the value of the most recent ouput! 

## Styling cell output
- Using Pandas for data analysis
- > import pandas as pd
- > df_weather = pd.read_csv ('weather.csv')
- > df_weather (for displaying formatted o/p)
- > df_weather.style.highlight_max () ( highlight max vals)
- choose subsets , colors etc

