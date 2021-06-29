---
title: "The Koda api"
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

To access the KoDa data the user has to interact via the [KoDa API](./KoDaAPI.md).  The KoDa API allows the user to access the raw GTFS data or make more advanced searches in the [KoDa database](./KoDaDatabase.md) via special API calls.

# KoDa Database

The raw data has been downloaded from [trafiklab.se](https://www.trafiklab.se/) and stored in its raw original GTFS format but the data has also been imported into a [Cassandra](https://cassandra.apache.org/) database. FOr more information on data formats and how to use the KoDa Cassandra database please refer to the [KoDa Database page](./KoDaDatabase.md) 

# Example of usage

In order to help users how the KoDa database and services can be used we have prepared a number of [examples](./examples.md) that illustrate some of the features with the KoDa system  
