
Content of each directory is described here:

all txt files contains 1-5mb.

# 1. Religious Texts
- Quranic Data
- Saheefeh Sajjadiah
- Kitab Tawheed (osool)

# 2. Social Networks
There are 50,000 posts in this data set from an Iranian social network(Cafejomle). Posts are divided into three files so that the size of the files is not large. This dataset contains three properties: user_id, date, and post text.

# 3. News
In this category, we have multiple files that contain data from news websites. Each file has a prefix that identifies the website that data come from.

## Data

### FarsNews
Files that start with the "fars-news" prefix contain data that have been gathered from [farsnews](https://www.farsnews.ir/) website.

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

# 4. Sports

In this cetegory, we have multiple files that contain data from sports websites. Each file has a prefix that identifies the website that data come from.

## Data

### Varzesh3
Files that start with the "varzesh3" prefix contain data that have been gathered from [varzesh3](https://www.varzesh3.com) website.

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

# 5. Literature
- Hafez/Saadi poesm
- All poets

# 6. Books
- The Little Prince

# 7. Financial Domain
