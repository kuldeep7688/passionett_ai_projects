# News Integration Project

## Integrating news from publicly available APIs to Passionett data

## Methodology

- Leverage free version of the NewsData.io api
- Regularly hit the api and dump the fetched articles in the PostGreSQL
- Articles older than 30 days will be deleted

## Hosting

- A Django API Endpoint will be released to interact with the data in PostGreSQL
