# data-512
Coursework related to DATA512


At minimum, you README file should:

## PROJECT GOALS
The goal of this project is to construct, analyze, and publish a dataset of monthly traffic on English Wikipedia from January 1, 2008 through August 30, 2020.

## DATA SOURCES
All data has been pulled from the Wikimedia REST API under the  Creative Commons Attribution-ShareAlike License.
https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License

https://wikitech.wikimedia.org/wiki/Analytics/AQS/Legacy_Pagecounts
The Wikimedia Foundation REST API terms of use: https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions.
Link to all relevant API documentation

Describe the values of all fields in your final data file.

| Column                  |    Format     |
|-------------------------|:-------------:|
| year                    |  YYYY         | 
| month                   |  MM           | 
| pagecount_all_views     | integer       | 
| pagecount_desktop_views | integer       | 
| pagecount_mobile_views  | integer       | 
| pageview_all_views      | integer       | 
| pageview_desktop_views  | integer       | 
| pageview_mobile_views   | integer       | 


List any known issues or special considerations with the data that would be useful for another researcher to know. For 
example, you should describe that data from the Pageview API excludes spiders/crawlers, while data from the Pagecounts API does not.

