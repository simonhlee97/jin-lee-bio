## Chicago Cubs (MLB)

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "width": "container",
  "data": {"url" : "assets/charts/data/cubs.csv"},
  "mark": "circle",
  "encoding": {
    "x": {"field": "quantitative", "field": "Quarter", "sort": "ascending"},
    "y": {"field": "quantitative", "field": "Name"}
  }
}
```

|Quarter | # of players | Percentage of Roster|
|-----|---- | -------|
|Q1   | 8   | 22.5%     |
|Q2   | 9   | 30%     |
|Q3   | 12   | 30%     |
|Q4   | 11   | 27.5%     |

note: *August 31st* is the most common cutoff date for youth football

Provided by <a href="https://www.sports-reference.com/sharing.html?utm_source=direct&utm_medium=Share&utm_campaign=ShareTool">Baseball-Reference.com</a>: <a href="https://www.baseball-reference.com/teams/CHC/2022-roster.shtml?sr&utm_source=direct&utm_medium=Share&utm_campaign=ShareTool#the40man">View Original Table</a><br>Generated 1/3/2023.