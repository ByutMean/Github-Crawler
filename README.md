# Github-Crawler
Crawler for github repository and user information

## About
In this project, I implement web crawler using Selenium, Beautiful soup and crawler using github rest api.

I will refactoring code soon.
 


<br>

## Crawled features

### Web crawler - repository

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

### Web crawler - user
| data        | data type |
| ----------- | --------- |
| commit      | int       |
| code add    | int       |
| code delete | int       |
| star        | int       |

### Api - repository
| data          | data type |
| ------------- | --------- |
| Description   | str       |
| Created date  | date      |
| Fork          | int       |
| Watch         | int       |
| Star          | int       |
| Main language | str       |
| Open issue    | int       |

### Api - user
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

```Api-repository``` , ```Web_crawler-repository``` - This code allows you to obtain repository information.

```git_issue``` , ```git_pull_request``` - This code allows you to obtain issue and pull request.

```Api_user``` , ```Web_crawler-user``` - This code allows you to obtain user information.


## Configuration
```
python
requests
pandas
selenium
BeautifulSoup
```