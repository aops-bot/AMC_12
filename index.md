## [Problems & Solutions](https://artofproblemsolving.com/wiki/index.php?title=AMC_12_Problems_and_Solutions)

[stats.json](https://github.com/aops-bot/AMC_12/blob/A/2011/stats.json) contains *Item Difficulty* statistics compiled from [AMC reports](http://amc-reg.maa.org/reports/generalreports.aspx) for U.S. participants in years 2011 - 2018. While the currently completed problem set range is determined by [config.json](https://github.com/aops-bot/AMC_12/blob/master/config.json)

```javascript
// stats.json
{ "1": { "A": 3.32, "B": 0.98, "C": 93.74, "D": 0.78, "E": 0.17, 
         "Omits": 0.99, "Answer": "C" }
         
// config.json
{
  "name": "AMC_12",
  "version": ["A"],
  "year": { "min": 2011, "max": 2013 },
  "problem": { "min": 1, "max": 25 }
}
```
