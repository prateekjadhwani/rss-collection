# rss-collection
A collection of all the rss feeds that can be used via an ajax call.
The json file can be found at [rss.json](http://prateekjadhwani.github.io/rss-collection/rss.json).

## Feed Sites

These are the currently available sites added to the *rss-collection*. Please feel free to add more.

| Name | Categories |
|------|------------|
| Times Of India | Top Stories |
| Wired | Top Categories, Business, Design, Science |
| xkcd | Humor |

## How to use

The json file is hosted on github. So you will simply need to call fetch the json file via ajax. The response object is an *Array* of rss site object. This is what it holds

| key | description | example value |
|-----|-------------|---------------|
| name | The name of the channel | "Wired" |
| rss | The url of the rss feed | "http://feeds.wired.com/wired/index" |
| category | The category of the feed | "top" |


## Categories Covered

The categories covered currently are as follows

| Category Name | Description |
|---------------|-------------|
| top | The Top Stories rss feed |
| business | Stories related to Business |
| design | _needs description_ |
| humor | Mostly comedy |
| science | Feeds related to Science |