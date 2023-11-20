
# Cricket-World-Cup-Analytics

In this T20-Cricket-Data-Analytics Project, I've taken a comprehensive T20 Cricket World-Cup data from the Code Basics platform. This dataset contains information about batsmen, bowlers, match details, and player profiles. I have use Microsoft Power BI for making the dashboard, Python and Microsoft Excel for data transformation and cleaning. Using the dashboard, we can easily analyse the data of each players so that we can choose our best playing Top 11 players.



[![MIT License](https://camo.githubusercontent.com/d10e346678b885e7ebed0f04e8a2e0874c276520997b070623819cfea2f02d8a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f706f7765725f62692d4632433831313f7374796c653d666f722d7468652d6261646765266c6f676f3d706f7765726269266c6f676f436f6c6f723d626c61636b)](https://choosealicense.com/licenses/mit/) 

[![GPLv3 License](https://camo.githubusercontent.com/a1b2dac5667822ee0d98ae6d799da61987fd1658dfeb4d2ca6e3c99b1535ebd8/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f707974686f6e2d3336373041303f7374796c653d666f722d7468652d6261646765266c6f676f3d707974686f6e266c6f676f436f6c6f723d666664643534)](https://opensource.org/licenses/) 

[![AGPL License](https://camo.githubusercontent.com/f737c8a9e60949e59f80fcca0b0019df76efb3c8ae56d38736bb93e44b447000/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f70616e6461732d2532333135303435382e7376673f7374796c653d666f722d7468652d6261646765266c6f676f3d70616e646173266c6f676f436f6c6f723d7768697465)](https://pandas.pydata.org/)




## Batting Dataset

| Match                | Team Innings | Batting Pos | Batsman Name            | Runs | Balls | 4s | 6s | SR     | Match ID    |
|----------------------|--------------|-------------|-------------------------|------|-------|----|----|--------|-------------|
| Namibia Vs Sri Lanka | Namibia      | 1           | Michael van Lingen      | 3    | 6     | 0  | 0  | 50     | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | 2           | Divan la Cock           | 9    | 9     | 1  | 0  | 100    | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | 3           | Jan Nicol Loftie-Eaton  | 20   | 12    | 1  | 2  | 166.66 | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | 4           | Stephan Baard           | 26   | 24    | 2  | 0  | 108.33 | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | 5           | Gerhard Erasmus(c)      | 20   | 24    | 0  | 0  | 83.33  | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | 6           | Jan Frylinck            | 44   | 28    | 4  | 0  | 157.14 | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | 7           | David Wiese             | 0    | 1     | 0  | 0  | 0      | T20I # 1823 |

## Bowling Dataset

| Match               | Bowling Team | Bowler Name                | Overs | Runs | Wickets | Economy | Match ID    |
|---------------------|--------------|----------------------------|-------|------|---------|---------|-------------|
| Namibia Vs Sri Lanka | Sri Lanka    | Maheesh Theekshana          | 4     | 23   | 1       | 5.75    | T20I # 1823 |
| Namibia Vs Sri Lanka | Sri Lanka    | Dushmantha Chameera         | 4     | 39   | 1       | 9.75    | T20I # 1823 |
| Namibia Vs Sri Lanka | Sri Lanka    | Pramod Madushan             | 4     | 37   | 2       | 9.25    | T20I # 1823 |
| Namibia Vs Sri Lanka | Sri Lanka    | Chamika Karunaratne         | 4     | 36   | 1       | 9       | T20I # 1823 |
| Namibia Vs Sri Lanka | Sri Lanka    | Wanindu Hasaranga de Silva  | 4     | 27   | 1       | 6.75    | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | Gerhard Erasmus            | 1     | 8    | 0       | 8       | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | David Wiese                | 4     | 16   | 2       | 4       | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | Bernard Scholtz            | 4     | 18   | 2       | 4.5     | T20I # 1823 |
| Namibia Vs Sri Lanka | Namibia      | Ben Shikongo               | 3     | 22   | 2       | 7.33    | T20I # 1823 |

## Match Info Dataset

| Team 1           | Team 2         | Winner          | Margin       | Ground  | Match Date | Match ID    |
|------------------|-----------------|-----------------|--------------|---------|------------|-------------|
| Namibia          | Sri Lanka       | Namibia         | 55 runs      | Geelong | 16-Oct-22  | T20I # 1823 |
| Netherlands      | U.A.E.          | Netherlands     | 3 wickets    | Geelong | 16-Oct-22  | T20I # 1825 |
| Scotland         | West Indies     | Scotland        | 42 runs      | Hobart  | 17-Oct-22  | T20I # 1826 |
| Ireland          | Zimbabwe        | Zimbabwe        | 31 runs      | Hobart  | 17-Oct-22  | T20I # 1828 |
| Namibia          | Netherlands      | Netherlands     | 5 wickets   | Geelong | 18-Oct-22  | T20I # 1830 |
| Sri Lanka        | U.A.E.          | Sri Lanka       | 79 runs     | Geelong | 18-Oct-22  | T20I # 1832 |
| Ireland          | Scotland        | Ireland         | 6 wickets   | Hobart  | 19-Oct-22  | T20I # 1833 |

## Players Info Dataset

| Name                  | Team        | Batting Style   | Bowling Style           | Playing Role        |
|-----------------------|-------------|-----------------|-------------------------|---------------------|
| Najmul Hossain Shanto | Bangladesh  | Left hand Bat   | Right arm Offbreak      | Top order Batter    |
| Soumya Sarkar         | Bangladesh  | Left hand Bat   | Right arm Medium fast   | Middle order Batter |
| Litton Das            | Bangladesh  | Right hand Bat  |                         | Wicketkeeper Batter |
| Shakib Al Hasan(c)    | Bangladesh  | Left hand Bat   | Slow Left arm Orthodox  | Allrounder          |
| Afif Hossain          | Bangladesh  | Left hand Bat   | Right arm Offbreak      | Allrounder          |
| Mosaddek Hossain      | Bangladesh  | Right hand Bat  | Right arm Offbreak      | Middle order Batter |



The 'batman.csv' dataset details the performance of individual batsmen, including their names, Total run they scored, Total ball they faced and strike Rate in each innings.
 
'bowling.csv' provides insights into bowlers, such as their total wickets, runs given, dot balls, and total economy.

'player info' contains player-specific information like their team, batting or bowling style, playing role, and description.

'match info' contains the details about matches, winner, margin and the ground name where the match is played.



## Dataset Screenshot

![Alt Text](https://user-images.githubusercontent.com/81465377/211144386-48070a65-7e8b-4370-af44-121b878b554b.jpg)