# Information-Visualization

Legend: 
This is a networkx graph. Each node (circle) represents a player in the Manchester City team. The width of the circle depends on the number of times that player has assisted another player. Big circles would indicate a higher number of assists and a small circle would indicate a lower number of assists.
The edges (lines) represents that there was an assist between the two nodes it’s connected to. The different colors represents the number of times the two players assisted each other. Dark blue indicates less than 3 times, red indicates a range between 3 and 6, light blue is for between 6 and 10 times and yellow shows less than 24 but more than 10. 

Findings:
The bigger circle indicates that they are typically mid fielders and the number of edges on each node indicates the playmaking quality of a player. 

Data & Method:
The data consists of players, which team they are playing for, the type of shots they’ve made and who they have assisted as well as the shot outcome. There are 9201 such rows. I narrow it down to players in the Manchester City team. 
After reading and analyzing the data, I decided to use only the player and assisted by columns from the data. There were rows which had no value for either the player column or assisted by column, so I dropped all the rows which had such values.
Further using networkx and matplotlib libraries I plotted the figure and legends.

Importance:
This figure helps identify important players. It also gives us a better understanding of each player’s performance and how can it be improved. It can help coaches devise game play strategies that take advantage of which pairs of players have the most number of assists.
