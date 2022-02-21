
## Data

### FarsNews
Files that start with the "fars-news" prefix contain data that have been gathered from [farsnews](https://www.farsnews.ir/) website, which is one of the most visited news websites in Iran.

#### Json File Structure 
Here you can see each item's structure in JSON files

| Attribute     | Description   | Type  |
|:-------------:|:-------------:|:-----:|
| `title`       | news title    |*string*|
| `abstract`    | abstract ( or description ) of each news | *string*|
| `paragraphs`    | list of divided text items on the website | *list(string)*|
| `cat`    | news category ( if exists ) | *string*|
| `subcat`    | news sub category ( if exists ) | *string*|
| `tags`    | list of associated tags on the website for each news| *list(string)*|
| `link`    |  news url | *string*|
