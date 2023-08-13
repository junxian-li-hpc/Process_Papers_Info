# Readme
提取每一个<hit>里author、title、venue、year、ee，如果有多个作者，放在excel里放在一个单元格中.

# Usage

```shell
pip install -r requires.txt
```

23/July/2023


## 13/Aug/2023
add config.json, in which you should fill the output excel file't columns name.
if there are some columns you have, but the dblp don't offer, you should fill them with no.
for example:
```json
{
  "columns": [
      {"name": "title", "title": "Title"},
      {"name": "no", "title": "ID"},
      {"name": "venue", "title": "Conference"},
      {"name": "no", "title": "CCF-Level"},
      {"name": "year", "title": "Year"},
      {"name": "no", "title": "Relevance"},
      {"name": "no", "title": "devices"},
      {"name": "ee", "title": "ref"},
      {"name": "no", "title": "Abstraction"},
      {"name": "no", "title": "KeyWords"},
      {"name": "no", "title": "Type"},
      {"name": "no", "title": "whichUse"},
      {"name": "no", "title": "Stauts"},
      {"name": "authors", "title": "Author"},
      {"name": "no", "title": "Organization"},
      {"name": "no", "title": "E-mail"}
  ]
}
																
```

