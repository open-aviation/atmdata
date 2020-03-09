---
layout: basic
title: Data sources
permalink: /sources/
---

This page presents various sources of open data that are currently available for aviation research.[^1] Our preference goes for data that is fully open. Some providers make data freely available, some ask for registration and may impose limits. We try to cover the license issue as much as we can. However, it is your responsibility to check the licensing terms carefully around the provided data before using it.

[^1]:Antonio Fernandez details carefully [on datascience.aero](https://datascience.aero/data-sources-aviation/) the common data sources existing in the aviation industry.  


## <i class="fas fa-satellite-dish"></i> Surveillance data, ADS-B, Mode S

Currently, the most easily accessible open flight data is undoubtedly ADS-B data. It is relatively simple to set up your Mode S/ADS-B receiver and start gathering data. Several crowd-sourced receiver networks also provide accesses to their live or historical data. Here are a few sources providing free access:

- [The OpenSky Network (live API)](https://opensky-network.org/apidoc/) allows you to obtain live flight data over the world for free, without registration.
- [The OpenSky Network (historical data)](https://opensky-network.org/data/impala) allows academics to access historical data flight data (including decoded ADS-B data and raw Mode S data) over the world for free. Registration is needed. Access to the historical database must be requested individually.
- [ADSB Exchange (live API)](https://www.adsbexchange.com/data/) allows you to obtain live flight data over the world freely. However, you must first feed data to ADS-B Exchange, and registration is also required.

For all the above sources, the data are provided for non-commercial use only. Specific agreements may be needed for commercial uses.

## <i class="fas fa-plane"></i> Aircraft information, tail number, typecode, registration number

Several website provide databases of tail numbers, transponder hexcodes associated to an aircraft type. Such information is precious when analysing aircraft trajectories.

- [Junzi's aircraft database](https://junzis.com/adb/) stopped updating in 2018 with about 150k frames;
- The OpenSky Network [aircraft database](https://opensky-network.org/aircraft-database) contains more than 460k frames;
- Some Regional Monitoring Agencies (RMA) provide an open access to data matching aircraft registered in their area, specifically in [Europe](https://www.eurocontrol.int/rmalive/operatorList.do) or in the [Middle-East](midrma.com/en/rvsm);
- [airport-data.com](http://www.airport-data.com/api/doc.php) is a comprehensive airport and aircraft database free to request but you may officially not download the full database;
- [doc8643.com](https://doc8643.com/) provides technical information related to many kinds of aircraft, as described in ICAO DOC 8643. See also [aircraft type](https://www.icao.int/publications/DOC8643/Pages/Search.aspx) and [manufacturers](https://www.icao.int/publications/DOC8643/Pages/Manufacturers.aspx)
- [airwar.ru](http://airwar.ru/) is a comprehensive catalogue of technical data of aircraft (in Russian)

## <i class="fas fa-rocket"></i> Aircraft and engine performance

Much of the performance related data are kept closed by manufacturers. Here is a list of open data that are available:

- [OpenAP](https://github.com/junzis/openap/) contains aircraft performance parameters for around 20 most common commercial aircraft. The Open Aircraft Performance Model is constructed using only open data and open models. It includes performance data regarding aircraft characteristics, drag polar, engine performances, and kinematic models.
- [ICAO Aircraft Engine Emissions Databank](https://www.easa.europa.eu/easa-and-you/environment/icao-aircraft-engine-emissions-databank) contains the most comprehensive list of engine emission data. It is a database maintained by ICAO and is regularly updated.

## <i class="fas fa-globe"></i> Airports, airspaces, ATS routes and navigational points

Many sources on the Internet are somehow redundant. They overlap quite well but some sources are more precise than others in particular areas of the world:

- The [FAA Aeronautical Data Delivery Service](https://adds-faa.opendata.arcgis.com/) provides a comprehensive database of relevant information over their airspace using standard format.
- [OurAirports](https://ourairports.com/) is a free site where visitors can explore the world's airports. It has been launched after Australia forced the US to close their [DAFIF database](https://en.wikipedia.org/wiki/DAFIF) to the general public. Information about airports, even shutdown, and their runways is available, searchable and downloadable.
- The API from [wikidata](https://www.wikidata.org/) could be used for all kind of
  [air transport infrastructure](https://commons.wikimedia.org/wiki/Category:Air_transport_infrastructure), like [airports](https://commons.wikimedia.org/wiki/Category:Airports), [taxiways](https://commons.wikimedia.org/wiki/Category:Taxiways) and [runways](https://commons.wikimedia.org/wiki/Category:Runways). You may run an [example request](https://w.wiki/FyU) for reference.
- Openstreetmap [overpass API](https://wiki.openstreetmap.org/wiki/Overpass_API) provides very precise information about airports, including gates, runways, parking positions and more.  
  See an [example](https://www.openstreetmap.org/node/4079636007#map=17/51.47123/-0.45934&layers=TD) at London Heathrow airport. The [traffic](https://traffic-viz.github.io/) library wraps these calls for you.

## <i class="fas fa-umbrella"></i> Weather

The following websites provide a large history of METAR data.  
METARs report basic weather information around airports:
- <http://www.ogimet.com/index.phtml.en>
- <https://mesonet.agron.iastate.edu/request/download.phtml>

The following website provides METAR, TAF and SIGMET history:
- <http://www.aviationwxchartsarchive.com/product/sigmet>

Miscellaneous:
- The Japanese Meteorological Agency 気象庁 provides weather information datasets on their [website](https://www.data.jma.go.jp/developer/index.html) (in Japanese).


## <i class="fas fa-desktop"></i> Live data for airspace usage

Some providers publish information about the current state of the network:
- Eurocontrol provide information about the current state of the network with regulation information on their [homepage](https://www.eurocontrol.int/);
- You may apply for access to the [FAA SWIM live feed](https://scds.swim.faa.gov/);

## <i class="fas fa-plane-departure"></i> Developer API from airlines and airports

Many airports and airlines provide an access to their API after you register for an API key:  
*(in alphabetic order)*

- Airports:
    - [Amsterdam Schiphol](https://developer.schiphol.nl/) airport in the Netherlands;
    - [Finavia](https://developer.finavia.fi/) maintains Finland's airport network;
    - [Frankfurt](https://developer.fraport.de/) airport in Germany;
    - [Swedavia](https://apideveloper.swedavia.se/) owns and operates the major airports of Sweden;

- Airlines
    - [Air France and KLM](https://developer.airfranceklm.com/);
    - [British Airways](https://developer.iairgroup.com/british_airways);
    - [Lufthansa](https://developer.lufthansa.com/);
    - [Singapore Airlines](https://developer.singaporeair.com/docs/Flight_Status/);

## <i class="fas fa-subway"></i> Miscellaneous transportation data

*(in alphabetic order)*

- French [Transport Data National Access Point](https://transport.data.gouv.fr/)  
  with few data sources related to [aviation](https://transport.data.gouv.fr/datasets?type=air-transport) (in French)
- Japanese [Public Transportation Open Data Center](https://www.odpt.org/)  
  with a specific focus on [air transportation data](https://ckan.odpt.org/dataset?tags=%E8%88%AA%E7%A9%BA) (in Japanese)
