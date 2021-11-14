* Language: Python3
* Regex: `(?<="reference": ")[0-9]*`
* Sample:
```
"reference": "12231123231"
```
* Expected Match:
```
12231123231
```

* Language: Python3
* Regex: `[\u00BC~\u00BE]+|[\u2150~\u215F]+`
* Sample:
```
2 ¼
```
* Expected Match:
```
¼
```
