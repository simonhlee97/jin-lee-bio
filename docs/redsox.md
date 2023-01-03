## Boston Red Sox (MLB)

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "width": "container",
  "data": {"url" : "assets/charts/data/redsox.csv"},
  "mark": "circle",
  "encoding": {
    "x": {"field": "quantitative", "field": "Quarter", "sort": "ascending"},
    "y": {"field": "quantitative", "field": "Name"}
  }
}
```


|Quarter | # of players | Percentage of Roster|
|-----|----- | -------|
|Q1   | 11   | 27.5%     |
|Q2   | 14   | 35%     |
|Q3   | 9    | 22.5%     |
|Q4   | 6    | 25%     |

note: August 31st is the most common cutoff date for youth football

Provided by <a href="https://www.sports-reference.com/sharing.html?utm_source=direct&utm_medium=Share&utm_campaign=ShareTool">Basketball-Reference.com</a>: <a href="https://www.basketball-reference.com/teams/IND/2023.html?sr&utm_source=direct&utm_medium=Share&utm_campaign=ShareTool#roster">View Original Table</a><br>Generated 12/30/2022.