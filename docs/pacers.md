## Indiana Pacers (NBA)

```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "width": "container",
  "data": {"url" : "assets/charts/data/pacers.csv"},
  "mark": "circle",
  "encoding": {
    "x": {"field": "quantitative", "field": "Quarter", "sort": "ascending"},
    "y": {"field": "quantitative", "field": "Player"}
  }
}
```

|Quarter | # of players | Percentage of Roster|
|-----|---- | ------- |
|Q1   | 8   | 47%     |
|Q2   | 5   | 29.4%     |
|Q3   | 2   | 11.8%     |
|Q4   | 2   | 11.8%     |

note: *August 31st* is the cutoff date for [youth basketball](https://www.usab.com/youth/development/youth-basketball-guidelines.aspx)

Provided by <a href="https://www.sports-reference.com/sharing.html?utm_source=direct&utm_medium=Share&utm_campaign=ShareTool">Basketball-Reference.com</a>: <a href="https://www.basketball-reference.com/teams/IND/2023.html?sr&utm_source=direct&utm_medium=Share&utm_campaign=ShareTool#roster">View Original Table</a><br>Generated 12/30/2022.