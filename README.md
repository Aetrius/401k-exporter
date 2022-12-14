# 401k πΈπ Dump & Exporter

This project is utilized to provide crypto data to Prometheus. Starting as a stand alone config file, and eventually will be a database.


## Features

- Prometheus Exporter
- Dockerized

## Deployment

To deploy this project run

```bash
  git clone <project.git>
  sudo docker-compose up -d
```
## Add More Metrics

Append the url section with additional urls using the YAML array string syntax shown below with a hypen and the url in quotes. 
Please note you will need to target the url of a specific page with a coin based on how the scraper is designed.

```
    metrics:
      vanguard:
        qty: 13515
```

## Authors

- [@Aetrius](https://www.github.com/Aetrius)


## Roadmap

- Additional Query Metrics

## Related Sources
[Live Coin Watch](https://www.livecoinwatch.com/price/Cardano-ADA)

[Web Scrape Resource](https://www.scrapingbee.com/blog/web-scraping-go/)
