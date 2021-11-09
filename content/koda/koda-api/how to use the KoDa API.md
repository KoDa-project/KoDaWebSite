---
title: "Usage"
---

# How to use the KoDa API

## Quick Test
To test that the API is live and the server is not down try 
[https://api.koda.trafiklab.se/KoDa/api/v2/hello](https://api.koda.trafiklab.se/KoDa/api/v2/hello)

## Normal Usage

The API has two primary modes of accessing the data: 
1. downloading the historical raw GTFS data as they were retrieved from TrafikLab at the time of download.
The KoDa API Swagger documentation lists the available endpoints and query parameters to use for downloading historical data. It can be found at  
[https://koda.linkoping-ri.se/KoDa/api/v2/swagger/](https://koda.linkoping-ri.se/KoDa/api/v2/swagger/)

3. working with the processed data stored in a Cassandra database (only available for users with KoDa JupyterHub access).

## Request of access keys

An access key is required to gain access to the KoDa API. The access key is requested thruogh the Samtrafikens and Trafiklabs open data API administrartion web pages. [https://need.correct.url/here](https://https://need.correct.url/here)


