## Chicago Bulls (NBA)

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "width": "container",
  "data": {"url" : "assets/charts/data/bulls.csv"},
  "mark": "circle",
  "encoding": {
    "x": {"field": "quantitative", "field": "Quarter", "sort": "ascending"},
    "y": {"field": "quantitative", "field": "Player"}
  }
}
```

|Quarter | # of players | Percentage of Roster|
|-----|---- | -------|
|Q1   | 6   | 37.5%     |
|Q2   | 1   | 6.3%     |
|Q3   | 5   | 31.3%     |
|Q4   | 4   | 25%     |

note: *August 31st* is the cutoff date for [youth basketball](https://www.usab.com/youth/development/youth-basketball-guidelines.aspx)

Provided by <a href="https://www.sports-reference.com/sharing.html?utm_source=direct&utm_medium=Share&utm_campaign=ShareTool">Basketball-Reference.com</a>: <a href="https://www.basketball-reference.com/teams/CHI/2023.html?sr&utm_source=direct&utm_medium=Share&utm_campaign=ShareTool#roster">View Original Table</a><br>Generated 12/31/2022.
