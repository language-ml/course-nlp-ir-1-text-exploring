
## Intro
In this folder, we have multiple files that contain data from news websites. Each file has a prefix that identifies a part of the URL that data come from.

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


### Donya-e-Eqtesad
Files that start with the "donya-e-eqtesad" prefix contain data that have been gathered from [donya-e-eqtesad](http://donya-e-eqtesad.com/) newspaper.
#### Json File Structure 
Here you can see each item's structure in JSON files

| Attribute     | Description   | Type  |
|:-------------:|:-------------:|:-----:|
| `newspaper_code`       | newspaper code    |*string*|
| `category`    | news category | *string*|
| `title`    | news title | *string*|
| `tags`    | list of associated tags on the website for each news| *list(string)*|
| `abstract`    | abstract ( or description ) of each news | *string*|
| `paragraphs`    | list of divided text items on the website | *list(string)*|