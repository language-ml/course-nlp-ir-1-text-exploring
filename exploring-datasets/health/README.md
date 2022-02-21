
## Intro
In this folder, we have multiple files that contain data from news websites. Each file has a prefix that identifies a part of the URL that data come from.

## Data

### Namnak
Files that start with the "namnak" prefix contain data that have been gathered from health section of [namnak](https://namnak.com/) website, which is one of the most visited websites in Iran.

#### Json File Structure 
Here you can see each item's structure in JSON files

| Attribute     | Description   | Type  |
|:-------------:|:-------------:|:-----:|
| `title`       | news title    |*string*|
| `abstract`    | abstract ( or description ) of each news | *string*|
| `paragraphs`    | list of divided text items on the website | *list(string)*|
| `categories`    | hierarchal news category | *string*|
| `tags`    | list of associated tags on the website for each news| *list(string)*|
| `link`    |  news url | *string*|

### Hidoctor
Files that start with the "hidoctor" prefix contain data that have been gathered from health section of [hidoctor](https://www.hidoctor.ir/) website, which is one of the most visited health websites in Iran.

#### Json File Structure 
Here you can see each item's structure in JSON files

| Attribute     | Description   | Type  |
|:-------------:|:-------------:|:-----:|
| `title`       | news title    |*string*|
| `paragraphs`    | list of divided text items on the website | *list(string)*|
| `tags`    | list of associated tags on the website for each news| *list(string)*|
| `link`    |  news url | *string*|