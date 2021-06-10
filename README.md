# Euro2021
Excel Workbook to record results for the Euro 2021 Football Championships. The Workbook automatically updates Tables and Qualifying based on UEFA rules without any Macros.

## User Input Tabs
There are two tabs where users can input the scores, cards, and penalties:

1) Group Match Input - For all the Groups Games
2) Knockout Match Input - For all the Knockout Games

### Group Match Input
For the first four games, of each Group, each Team needs the below cells to be completed:				
1)	Team (A or B) Goals		
2)	Team (A or B) YCs - Number of Yellow Cards received by the Team. If a Red Card is issued for two Yellow Cards, then Yellow Cards should not be counted.			
3)	Team (A or B) RCs - Number of Red Cards received by the Team. If a player receives a yellow card followed by a Red Card, then this counts as 1 Red Card and 1 Yellow Card.		
				
For the final two games, of each Group, each Team needs to have the above completed. However, if, at the end of the game, the game is drawn, and the teams are level in the table with no other team level with them, then a penalties will be taken. These must be recorded in the Team A or B Penalties cell.				
				
### Knockout Match Input				
For the all the knockout games each Team needs to have the Team (A or B) Goals cell completed. If the scores are tided after Full-Time, the game will go into Extra Time.

The number of goals each team has in total needs to be entered into the Team (A or B) AET cells. If the scores are still level, then Penalties must be taken.

The number of penalties scored by each team needs to be entered into the Team (A or B) Penalties cells. The XL Workbook will automaticaly detect if the AET or Penalties cells need to be completed and will highlight the required cell in orange.
