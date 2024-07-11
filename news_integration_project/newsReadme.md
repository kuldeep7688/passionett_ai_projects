# News Integration Project

## Integrating news from publicly available APIs to Passionett data

## Methodology

- Leverage free version of the NewsData.io api
- Regularly hit the api and dump the fetched articles in the PostGreSQL
- Articles older than 30 days will be deleted

## Hosting

- A Django API Endpoint will be released to interact with the data in PostGreSQL

### News

- [NewsData.io](http://NewsData.io)
  - Link https://newsdata.io/pricing
  - 200 hits a day
  - We can centrally hit the api every day 100 times to get the data
  - And centrally maintain the data and provide to users
  - https://newsdata.io/blog/integrate-free-news-api-into-your-application/
- News API
  - Link https://newsapi.org/pricing
  - https://github.com/SauravKanchan/NewsAPI (Github solution to leverage the api without paying)
- The NewsAPI
  - Link : https://www.thenewsapi.com/register
- PyGoogleNews Python Package
  - using it, we can get blocked
  - Link : https://github.com/kotartemiy/pygooglenews
- WorldNews API
  - https://worldnewsapi.com/
