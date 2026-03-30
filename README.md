# OMSA-CSE-6242

nfl_combine_web_scrape --> 
  Scrape mockdraftable.com
  -> Get 'nfl_combine_data.csv'

nfl_verse_player_stats --> Get Player Stats
  use the position, player name, college, and draft year from nfl_combine_data to get a match to nfl_data on pro-football-reference through the nflreadpy library
  Filter for data with a high or perfect confidence
  Use those to get the player stats through 1999 to 2026
  -> Overall file could use cleaning up
  -> Get 'nfl_combine_stats.csv' & 'player_season_stats.csv'
