---
title: "The Koda Projekt"
menu: "main"
translationKey: "koda"
url: "/koda"
weight: 1
layout: single
sidebar: true
---

# The KoDa project

Kollektivtrafikens Datalabb (KoDa) aims to collect, store, and provide a historical open data record of the real time and static data that is provided by in the Trafiklab.se open data service. There are to access the collected data in this page we give references on how to use the REST API interface. 

# KoDa API

To access the KoDa data the user has to interact via the [KoDa API](https://api.koda.trafiklab.se/KoDa/api/v2/swagger/). The KoDa API allows the user to access the raw static and real time GTFS data via special API calls.

But inorder to gain acccess to the data the user has to request an API key from Trafiklab.  This can be done via the [Trafiklabs access key portal](https://www.trafiklab.se/hur-gor-jag)

# KoDa Database

The raw GTFS and GTFS-rt data has been downloaded from [trafiklab.se](https://www.trafiklab.se/) and stored in its raw original GTFS format but the data has also been imported into a [Cassandra](https://cassandra.apache.org/) database. 

To access the structured database a suer as to get an acount for the KoDa JupyterHub server. To requset an account please contact 'koda(at)ri.se'.

For more information on data formats and how to use the KoDa Cassandra database please refer to the [KoDa Database page](./KoDaDatabase.md) 

# Example of usage

In order to help users how the KoDa database and services can be used we have prepared a number of [examples](./examples.md) that illustrate some of the features with the KoDa system  
