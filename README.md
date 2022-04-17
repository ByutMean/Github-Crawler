# Github-Crawler
Crawler for github repository and user information

## About
In this project, I implement web crawler using Selenium, Beautiful soup and crawler using github rest api.

I will refactoring code soon.



<br>

## Crawled features

<bold>Web crawler - repository

| data               | data type |
| ------------------ | --------- |
| tag                | str       |
| readme             | str       |
| language           | str       |
| num of contributor | int       |
| open pull-request  | int       |
| total pull-request | int       |
| total open issue   | int       |
| repository commit  | int       |

<bold>Web crawler - user
| data        | data type |
| ----------- | --------- |
| commit      | int       |
| code add    | int       |
| code delete | int       |
| star        | int       |

<bold>Api - repository
| data          | data type |
| ------------- | --------- |
| Description   | str       |
| Created date  | date      |
| Fork          | int       |
| Watch         | int       |
| Star          | int       |
| Main language | str       |
| Open issue    | int       |

<bold>Api - user
| data        | data type |
| ----------- | --------- |
| type        | str       |
| company     | str       |
| description | str       |
| repository  | int       |
| gist        | int       |
| follower    | int       |
| following   | int       |
| created     | date      |


## Key file
Check your token before using the code

```g``` - This code allows you to obtain repository information.

```git_api``` - This code allows you to obtain user information.


## Configuration
```
python
requests
pandas
selenium
BeautifulSoup
```