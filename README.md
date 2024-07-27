# FIFA-19-Analysis

**FIFA** is one of the most popular football video games developed by EA Sports. It simulates real-life football matches and allows players to control football teams composed of real-life players. Each player in the game has attributes that affect their performance on the virtual pitch, such as speed, shooting accuracy, and defensive skills. These attributes are quantified in a dataset, which provides a wealth of information that can be analyzed to gain insights into player and team performance.

### **Understanding the Fifa19 Dataset**

The Fifa19 dataset contains detailed information about football players featured in the FIFA 19 video game. The dataset includes attributes such as:

- **Name**: The player's name.
- **Age**: The player's age.
- **Nationality**: The player's nationality.
- **Overall**: The player's overall rating.
- **Potential**: The player's potential rating.
- **Club**: The club the player is affiliated with.
- **Value**: The player's market value.
- **Position**: The player's primary playing position.
- **Various Skills**: Specific attributes related to the player's abilities, such as goalkeeping skills (GK Diving, GK Handling, etc.) and field skills (Ball Control, Crossing, etc.).

**Data Dictionary for Fifa19 Dataset**

Please Download the File from here [FIFA_Processed_Data.xlsx](https://docs.google.com/spreadsheets/d/1oDjCd0LmqE87dIkQkr4aXdd1lzs_lTIE/edit?usp=sharing&ouid=107283585265712393366&rtpof=true&sd=true).

| Column Name | Data Type | Description |
| --- | --- | --- |
| ID | Integer | Unique identifier for each player |
| Name | String | Player's name |
| Age | Integer | Player's age |
| Nationality | String | Player's nationality |
| Overall | Integer | Player's overall rating |
| Potential | Integer | Player's potential rating |
| Club | String | Club the player is affiliated with |
| Value | String | Market value of the player (e.g., "€105M") |
| Wage | String | Player's weekly wage (e.g., "€200K") |
| Preferred Foot | String | Player's preferred foot (e.g., "Left", "Right") |
| International Reputation | Integer | Player's international reputation rating (1-5 scale) |
| Weak Foot | Integer | Player's weak foot rating (1-5 scale) |
| Skill Moves | Integer | Player's skill moves rating (1-5 scale) |
| Work Rate | String | Player's work rate (e.g., "High/Medium") |
| Body Type | String | Player's body type (e.g., "Normal", "Lean") |
| Position | String | Player's primary playing position |
| Jersey Number | Integer | Player's jersey number |
| Joined | String | Date the player joined the current club |
| Contract Valid Until | Integer | Year until the player's contract is valid |
| Height | String | Player's height (e.g., "5'7") |
| Weight | String | Player's weight (e.g., "159lbs") |
| LS, ST, RS, etc. | String | Player's ratings for different positions on the field |
| GK Diving | Integer | Goalkeeping diving skill |
| GK Handling | Integer | Goalkeeping handling skill |
| GK Kicking | Integer | Goalkeeping kicking skill |
| GK Positioning | Integer | Goalkeeping positioning skill |
| GK Reflexes | Integer | Goalkeeping reflexes |
| Ball Control | Integer | Player's ball control skill |
| Crossing | Integer | Player's crossing skill |
| Jumping | Integer | Player's jumping ability |
| Long Passing | Integer | Player's long passing skill |
| Long Shots | Integer | Player's long shots skill |

### **Task Description**

Your objective is to design a comprehensive dashboard using Tableau to visualize different aspects of the Fifa19 dataset. The dashboard should include four distinct charts, each providing unique insights.

### **Tasks**

1. **Top 10 Clubs by Player Value**
    - Create a chart that highlights the top 10 clubs based on the highest overall value of their players.
    - Display the percentage share of each club within this top 10 group.
2. **Top 10 Players by Market Value**
    - Develop a chart showcasing the top 10 players with the highest market value.
    - Include their overall scores and enhance the chart with tooltips that reveal each player's age, club, and nationality.
3. **Top 10 Players by Growth Potential**
    - Identify players with the greatest growth potential by creating a calculated field that determines the difference between a player's current overall rating and their potential rating.
    - Display the top 10 players based on this growth potential criterion and set the criteria for age as from 16 to 20 as the teams would like to focus on young players.
4. **Top 5 Goalkeepers by Average Goalkeeping SkillsCalculate the average of various goalkeeping skills to find the top 5 goalkeepers.Use columns such as [GK Diving], [GK Handling], [GK Kicking], [GK Positioning], [GK Reflexes], [Ball Control], [Crossing], [Jumping], [Long Passing], and [Long Shots].Rank the goalkeepers accordingly and display the results.**

**5. Top 10 Players from each position: Your objective is to create an interactive dashboard in Tableau that allows users to select a position and view the top 10 players for that position based on their overall rating. Create a parameter that enables the selection of different player positions. Develop a calculated field to filter players based on the selected position. Create a ranking field to rank players by their overall rating within the selected position. Filter the data to show only the top 10 players for the selected position. Design a bar chart to display these top 10 players, including their names and overall ratings. Enhance the chart with tooltips that show additional player details such as club, nationality, and age. Assemble these components into a cohesive and interactive dashboard that dynamically updates based on the selected position.**

**6. Create a Dashboard:** Assemble the four charts into a single, cohesive dashboard. Ensure that the dashboard is interactive and visually appealing, providing clear and insightful information at a glance.
