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

note: August 31st is the most common cutoff date for youth baseball

Provided by <a href="https://www.sports-reference.com/sharing.html?utm_source=direct&utm_medium=Share&utm_campaign=ShareTool">Baseball-Reference.com</a>: <a href="https://www.baseball-reference.com/teams/BOS/2022.shtml?sr&utm_source=direct&utm_medium=Share&utm_campaign=ShareTool#the40man">View Original Table</a><br>Generated 1/3/2023.