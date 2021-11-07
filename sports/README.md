
## Intro
In this folder, we have multiple files that contain data from sports websites. Each file has a prefix that identifies a part of the URL that data come from.

## Data

### Varzesh3
Files that start with the "varzesh3" prefix contain data that have been gathered from [varzesh3](https://www.varzesh3.com) website, which is one of the most visited websites in Iran.

#### Json File Structure 
Here you can see each item's structure in JSON files

| Attribute     | Description   | Type  |
|:-------------:|:-------------:|:-----:|
| `code`        | news code     | *int* |
| `title`       | news title    |*string*|
| `abstract`    | abstract ( or description ) of each news | *string*|
| `paragraphs`    | list of divided text items on the website | *list(string)*|
| `tags`    | list of associated tags on the website for each news| *list(string)*|
| `link`    |  news url | *string*|

