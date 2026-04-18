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

**graphs - players from eda_nb**

x = ['arm_length_in', 'bmi', 'height_in','weight_lbs','wing_span_in','hand_size_in',
&ensp;&ensp;`x_by_position` - scatterplot of measurement by position
&ensp;&ensp;`avg_x_by_season_pos` - avg measurement by season for by position
&ensp;&ensp;`box_plot_x_by_position` - boxplot of measurement by position

**graphs - roster**

&ensp;&ensp;`team_avg_height_performance` - avg height vs performance for each team
&ensp;&ensp;`team_avg_weight_performance` - avg weight vs performance for each team

**tables from eda_nb**

&ensp;&ensp;`feature_importance.csv` - CSV of the feature importance for each position
&ensp;&ensp;`outlier_table.csv`- Number of outliers and % of outliers for each measurement for each position
&ensp;&ensp;`model_summary.csv`- CSV of the summary/stats of baseline vs anthro models for each position 





