## Indianapolis Colts (NFL)

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "width": "container",
  "data": {"url" : "assets/charts/data/colts.csv"},
  "mark": "circle",
  "encoding": {
    "x": {"field": "quantitative", "field": "Quarter", "sort": "ascending"},
    "y": {"field": "quantitative", "field": "Player"}
  }
}
```

|Quarter | # of players | Percentage of Roster|
|-----|---- | -------|
|Q1   | 15   | 24.2%     |
|Q2   | 16   | 25.8%     |
|Q3   | 21   | 33.9%     |
|Q4   | 10   | 16.1%     |

note: August 1st is the most common cutoff date for youth football

Provided by <a href="https://www.sports-reference.com/sharing.html?utm_source=direct&utm_medium=Share&utm_campaign=ShareTool">Pro-Football-Reference.com</a>: <a href="https://www.pro-football-reference.com/teams/clt/2022_roster.htm?sr&utm_source=direct&utm_medium=Share&utm_campaign=ShareTool#roster">View Original Table</a><br>Generated 1/1/2023.