# OMSA-CSE-6242


Revamped\
\
Notebooks\\
mockdraftable_Web_scrape --> Used to scrape https://www.mockdraftable.com/ for heihgt, weight, positions, colleges, hand_sizes, wing_span, and combine stats\
&nbsp;output: nfl_combine_data.csv
get_stats --> Used to get the player and roster stats
&nbsp;output:\
&ensp;def_model_data.csv --> CSV containing seasonal data for defensive players + anthropometric features/combine performance + flag for missing features\
&ensp;qb_model_data.csv --> CSV containing seasonal data for quarterbacks + anthropometric features/combine performance + flag for missing features\
&ensp;rb_model_data.csv -- > CSV containing seasonal data for running backs + anthropometric features/combine performance + flag for missing features\
&ensp;wr_model_data.csv --> CSV containing seasonal data for wide receivers and tight ends + anthropometric features/combine performance + flag for missing features\
&ensp;roster_model_data.csv --> CSV containing seasonal data for rosters + avg height/weight\
eda_nb --> Use RidgeCV to find relationship between Anthro features * Performance. Compares a baseline model vs model with anthrofeatures added
&nbsp;output: visualizaitons + model results
&nbsp; 

Results\\
