# OMSA-CSE-6242
Revamped

## Notebooks

**mockdraftable_Web_scrape** – Used to scrape https://www.mockdraftable.com/ for height, weight, positions, colleges, hand sizes, wing span, and combine stats  
&nbsp;&nbsp;output: `nfl_combine_data.csv`

**get_stats** – Used to get the player and roster stats  
&nbsp;&nbsp;output:  
&ensp;&ensp;`def_model_data.csv` – CSV containing seasonal data for defensive players + anthropometric features/combine performance + flag for missing features  
&ensp;&ensp;`qb_model_data.csv` – CSV containing seasonal data for quarterbacks + anthropometric features/combine performance + flag for missing features  
&ensp;&ensp;`rb_model_data.csv` – CSV containing seasonal data for running backs + anthropometric features/combine performance + flag for missing features  
&ensp;&ensp;`wr_model_data.csv` – CSV containing seasonal data for wide receivers and tight ends + anthropometric features/combine performance + flag for missing features  
&ensp;&ensp;`roster_model_data.csv` – CSV containing seasonal data for rosters + avg height/weight  

**eda_nb** – Uses RidgeCV to find relationship between Anthro features & Performance. Compares a baseline model vs model with anthro features added  
&nbsp;&nbsp;output: visualizations + model results

## Results
