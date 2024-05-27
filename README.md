# Fotmob_shotsdata_whole_league

For scraping all of the matches of a league:-
1. First search the league you want to scrape, inside that go to the matches and select 'By round' and then select Round 1
2. There you'll see 10 matches, click on the first match and collect the matchID from the link of that match. For example, if the MatchId is 4193450, the next matchId will be 4193451, that means the number increase by 1 gradually!
3. Download the teams_name_and_id.csv file, this contain "English Premiere League", "La Liga" and "Bundesliga" teams teamId according to their team name, if you want other leagues, make another excel file like this your own and use that!
4. Download .ipynb file and input that teams_name_and_id.csv file path and the first matchId into the code
5. Finally running the code, you can get all of the shots data of the league in  the "final_shots_df" dataframe! 
