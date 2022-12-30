## Boston Red Sox (MLB)

Quarter 1 = Jan, Feb, Mar

Quarter 2 = Apr, May, Jun

Quarter 3 = Jul, Aug, Sep

Quarter 4 = Oct, Nov, Dec


```vegalite
{
  "$schema": "https://vega.github.io/schema/vega-lite/v5.json",
  "width": "container",
  "data": {"url" : "assets/charts/data/redsox.csv"},
  "mark": "point",
  "encoding": {
    "x": {"field": "quantitative", "field": "Quarter", "sort": "ascending"},
    "y": {"field": "quantitative", "field": "Name"}
  }
}
```


Provided by <a href="https://www.sports-reference.com/sharing.html?utm_source=direct&utm_medium=Share&utm_campaign=ShareTool">Basketball-Reference.com</a>: <a href="https://www.basketball-reference.com/teams/IND/2023.html?sr&utm_source=direct&utm_medium=Share&utm_campaign=ShareTool#roster">View Original Table</a><br>Generated 12/30/2022.

|Total Count | Percentage of Roster|
|-----|----------|
|Q1   |40%       |
|Q2   |30%     |
|Q3   |20%     |
|Q4   |10%     |

