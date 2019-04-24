# video crawler

A brief description on crawling video resource

## Database Design

### Registered Table

make sure the crawler is validate.
include, 

### Rules Table

about the rules of xpath/jsonpath 

### Filter Table

use redis or no-sql.
bloomfilter repeated url


### Crawl Urls Table

start_urls

## Crawler Module Design

the main part in this project.
include, **proxy module , url manager module, request module,
parse module and download module etc.**

### Proxy Module

avoid ip banned

### Request/Crawl Module

control request priority through the request queue

include， **scheduler module， multithread download module，request queue module**

### PraseWeb Module

parse web html/json/xml。

if follow is **True**， return next url to the **UrlManager Module**

### Download Module

remote download video,
the way of segments

### UrlManager Module

Management send queue

## Function Extension Design

### Base Queue Plugin

### Selenium Plugin

### Download Pulgin

### CookiesPool  Plugin
