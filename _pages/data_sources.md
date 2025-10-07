---
layout: basic
title: Data sources
permalink: /sources/
---

This page presents various sources of open data that are currently available for aviation research. Our preference goes for data that is fully open. Some providers make data freely available, some ask for registration and may impose limits. We try to cover the license issue as much as we can. However, it is your responsibility to check the licensing terms carefully around the provided data before using it.



## <i class="fas fa-satellite-dish"></i> Surveillance data, ADS-B, Mode S

Currently, the most easily accessible open flight data is undoubtedly ADS-B data. It is relatively simple to set up your Mode S/ADS-B receiver and start gathering data. Several crowd-sourced receiver networks also provide accesses to their live or historical data. Here are a few sources providing free access:

- [The OpenSky Network (live API)](https://opensky-network.org/apidoc/) allows you to obtain live flight data over the world for free, without registration.
- [The OpenSky Network (historical data)](https://opensky-network.org/data/impala) allows academics to access historical data flight data (including decoded ADS-B data and raw Mode S data) over the world for free. Registration is needed. Access to the historical database must be requested individually.
- [ADS-B Exchange (live API)](https://www.adsbexchange.com/data/) allows you to obtain live flight data over the world freely. However, you must first feed data to ADS-B Exchange, and registration is also required.
- [Airplanes.Live](https://airplanes.live/): like many others live and historical data is available in some ways.
- [adsb.lol](https://adsb.lol/)
- [adsb.fi](https://adsb.fi/): new community of feeders who fled from ADS-B Exchange after it went commercial.
- [TheAirTraffic](https://theairtraffic.com/)


For all the above sources, the data are provided for non-commercial use only. Specific agreements may be needed for commercial uses.

## <i class="fas fa-plane"></i> Flight (or schedule) data

The following websites provides access to flight data, usually contains the origin, destination, number of passengers or aircraft information
- [🇪🇺 OPDI - Open Performance Data Initative](https://www.opdi.aero/) contains the flight data based on OpenSky network flight data, enhanced to contain flight events and phases, like off-vlock time, take-off, start of climb, cruise, top of descent, etc. The goal of the website is to provide a data platform, to support higher levels of transparency and reproducibility of performance related monitoring and associated analyses. 
- [🇺🇸 Bureau of Transportation Statistics Airlines, Airports and Aviation](https://www.bts.gov/topics/airlines-airports-and-aviation). The website contains a number of different datasets related to aviation, from on-time performance, over passenger and cargo numbers, ticket prices, fuel cost to airline financial data. 
- [🇪🇺 Aviation Data for Research](https://www.eurocontrol.int/dashboard/rnd-data-archive) contains all detailed flight information regarding flight departing and/or arriving from EUROCONTROL member states. The data is only publish with two-year delay and only include four months each year, which are March, June, September, and December. Access to this data need to be requested on the website.
- [🇧🇷 Dados Estatísticos, Agência Nacional de Aviação Civil (ANAC), Brazil](https://www.gov.br/anac/pt-br/assuntos/dados-e-estatisticas/dados-estatisticos) provides all flight information departing from and/or arriving at Brazil since 2000
- [🇮🇳 Flight Schedule Date, India](https://data.gov.in/resource/flight-schedule) contains the data regarding from AirSewa data, including data about the flight schedule, status, and airport services.
- [🇦🇺 Aviation Statistics, Australia](https://www.bitre.gov.au/statistics/aviation) contains domestic and international aviation statistics including airline activity, domestic on time performance, domestic airfares index, airfreight, airport traffic, general aviation activity, aviation fuel sales and air distances.
- [🇭🇰 Flight Information, Hong Kong](https://data.gov.hk/en-data/dataset/aahk-team1-flight-info) contains flight Information of Hong Kong International Airport, including data about the flight schedule, status, passenger/cargo flight. This web service returns historical data (previous calendar day) in 
JSON format.


## <i class="fas fa-plane"></i> Aircraft related data

Several website provide databases of tail numbers, transponder hexcodes associated to an aircraft type. Such information is precious when analysing aircraft trajectories.

Aircraft information:

- The OpenSky Network [aircraft database](https://opensky-network.org/aircraft-database) contains more than 460k frames;
- FAA's [aircraft database](https://www.faa.gov/airports/engineering/aircraft_char_database/aircraft_data) is an excel file containing the aircraft codes, associated BADA profiles, various aircraft characteristics, like dimensions, weights, wake category, etc.
- Some Regional Monitoring Agencies (RMA) provide an open access to data matching aircraft registered in their area, specifically in [Europe](https://www.eurocontrol.int/rmalive/operatorList.do) or in the [Middle-East](midrma.com/en/rvsm);
- [airport-data.com](http://www.airport-data.com/api/doc.php) is a comprehensive airport and aircraft database free to request but you may officially not download the full database;
- [doc8643.com](https://doc8643.com/) provides technical information related to many kinds of aircraft, as described in ICAO DOC 8643. See also [aircraft type](https://www.icao.int/publications/DOC8643/Pages/Search.aspx) and [manufacturers](https://www.icao.int/publications/DOC8643/Pages/Manufacturers.aspx)
- Boeing's [Airport Planning Manuals](https://www.boeing.com/commercial/airports/plan-manuals), that contain details for airport servicing of the aircraft.
- Airbus's [Airport and maintenance planning documents](https://aircraft.airbus.com/en/customer-care/fleet-wide-care/airport-operations-and-aircraft-characteristics/aircraft-characteristics) that contain details for airport servicing of aircraft.
- [airwar.ru](http://airwar.ru/) is a comprehensive catalogue of technical data of aircraft (in Russian)
- [Mictronics' aircraft DB](https://www.mictronics.de/aircraft-database/)
- [Junzi's aircraft database](https://junzis.com/adb/) with about 150k frames (stopped updating in 2018)


Transponder information:

- [Aircraft Comm-B capability database](https://github.com/junzis/gicb-db) contains a list of common Comm-B capabilities for a large number of aircraft Mode S transponders over the world.

## <i class="fas fa-rocket"></i> Aircraft and engine performance

Much of the performance related data are kept closed by manufacturers. Here is a list of open data that are available:

- [OpenAP](https://github.com/junzis/openap/) contains aircraft performance parameters for around 20 most common commercial aircraft. The Open Aircraft Performance Model is constructed using only open data and open models. It includes performance data regarding aircraft characteristics, drag polar, engine performances, and kinematic models.
- [ICAO Aircraft Engine Emissions Databank](https://www.easa.europa.eu/easa-and-you/environment/icao-aircraft-engine-emissions-databank) contains the most comprehensive list of engine emission data. It is a database maintained by ICAO and is regularly updated.

## <i class="fas fa-globe"></i> Airports, airspaces, ATS routes and navigational points

Many sources on the Internet are somehow redundant. They overlap quite well but some sources are more precise than others in particular areas of the world:

- The [EAD Basic](https://www.ead.eurocontrol.int/fwf-eadbasic/public/cms/cmscontent.faces?configKey=default.home.page) European AIS Database (EAD) is a free Public Access Service application for the general public, which  allows you to browse the  for a limited set of aeronautical information publications (AIP), given in pdf format. Registration is needed, and is free.
- [EUROCONTROL's Airport Corner](https://www.eurocontrol.int/tool/airport-corner) this is an airport-focused data repository, for largest European airports. The public version has limited data access, but still contains  runways, airport capacities and other information of interest. 
- The [FAA Aeronautical Data Delivery Service](https://adds-faa.opendata.arcgis.com/) provides a comprehensive database of relevant information over their airspace using standard format.
- The [FAA's AIP](https://www.faa.gov/air_traffic/publications/atpubs/aip_html/#:~:text=Aeronautical%20Information%20Publication%20%2D%20AIP), all FAA AIP information and links to other data.
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
- <https://aviationweather.gov/dataserver>
- <https://navlost.eu/>

The following website provides METAR, TAF and SIGMET history:

- <http://www.aviationwxchartsarchive.com/product/sigmet>

The US Aviation Weather Center - aviation weather data on the go:
- https://aviationweather.gov/
- API  access: https://aviationweather.gov/data/api/

[ECMWF's Integrated Forecasting System ](https://www.ecmwf.int/en/forecasts/documentation-and-support/changes-ecmwf-model?check_logged_in=1). Different forecast products. Requires login.

ERA5 reanalysis and other products available from [Climate Data Store](https://cds.climate.copernicus.eu/). Requires login (the same login as for ECMWF). 

Volcanic ash info:

- https://sacs.aeronomie.be/
- https://www.ospo.noaa.gov/products/atmosphere/vaac/other-vaacs.html


Miscellaneous:

- The Japanese Meteorological Agency 気象庁 provides weather information datasets on their [website](https://www.data.jma.go.jp/developer/index.html) (in Japanese).

## <i class="fas fa-headphones"></i> Noise

The European Aircraft Noise Services (EANS) <https://www.eans.net/> provides data from sensor devices across Europe. More specifically in the following countries:

- France: [bruitparif.fr](https://rumeur.bruitparif.fr/) in the Greater Paris area
- The Netherlands: [explane.org](https://reports.explane.org/nl/) or data from [NOMOS sensors](https://noiselab.casper.aero/ams/#page=actual) around Schiphol airport

## <i class="fas fa-smog"></i> Air quality

The European Environment Agency makes some measurements available through the [following interface](http://discomap.eea.europa.eu/map/fme/AirQualityExport.htm). More specifically in the following countries:

- France: the [Prév'air](http://www2.prevair.org/) database provides observation and forecast maps
- The Netherlands: a [webpage](https://www.luchtmeetnet.nl/) provided by the Dutch Ministry of Health (RIVM)

The Japanese National Institute for Environmental Studies provides historical data of air quality measurements:
- Japan: [National Institute for Environmental Studies](http://www.nies.go.jp/igreen/) (Japanese)

## <i class="fas fa-stats"></i> Statistics
Various aviation related statistics.
- [STATFOR](https://www.eurocontrol.int/dashboard/statfor-interactive-dashboard) a platform to suit the flight forecasting needs. Offers different views on fligths, airports, states by flight segments. Requires registration.
- [🇺🇸 Bureau of Transportation Statistics Airlines, Airports and Aviation](https://www.bts.gov/topics/airlines-airports-and-aviation). The website contains a number of different datasets related to aviation, from on-time performance, over passenger and cargo numbers, ticket prices, fuel cost to airline financial data.
- [EUROCONTROL's Our data](https://www.eurocontrol.int/our-data) quick access to various publicly available data on European aviation.
- [Aviation Intelligence Portal](https://ansperformance.eu/)  insights into various aviation performance areas, in support of the independent work of the Performance Review Commission (PRC).
- [Eurostat](https://ec.europa.eu/eurostat/web/main/data/database) different EU-wide statistics, transportation modes covered.

## <i class="fas fa-table-list"></i> Live data for airspace usage

Some providers publish information about the current state of the network:

- Eurocontrol provide information about the current state of the network with regulation information on their [homepage](https://www.eurocontrol.int/);
- You may apply for access to the [FAA SWIM live feed](https://scds.swim.faa.gov/);

## <i class="fas fa-plane-departure"></i> Developer API from airlines and airports

Many airports and airlines provide an access to their API after you register for an API key:  
_(in alphabetic order)_

- Airports:

  - [Amsterdam Schiphol](https://developer.schiphol.nl/) airport in the Netherlands;
  - [Avinor](https://avinor.no/en/corporate/services/flydata/flydata-i-xml-format) owns and operates the major airports of Norway;
  - [Dubai](https://www.dubaipulse.gov.ae/organisation/dubai-airports/service/dubai-airports-flight-info) airport;
  - [Finavia](https://developer.finavia.fi/) maintains Finland's airport network;
  - [Luxembourg](https://data.public.lu/en/datasets/arrivees-et-departs-de-laeroport-de-luxembourg/) airport;
  - [Hamburg](https://portal.api.hamburg-airport.de/) airport in Germany;
  - [Hong Kong](https://data.gov.hk/en-data/dataset/aahk-team1-flight-info) airport;
  - [Münster/Osnabrück](https://opendata.stadt-muenster.de/dataset/flugplandaten-des-flughafen-m%C3%BCnsterosnabr%C3%BCck-fmo) airport in Germany;
  - [Swedavia](https://apideveloper.swedavia.se/) owns and operates the major airports of Sweden;

- Airlines
  - [Air France and KLM](https://developer.airfranceklm.com/);
  - [Lufthansa](https://developer.lufthansa.com/);

## <i class="fas fa-calendar-days"></i> Schedules from airlines

Some airlines offer timetables in a machine-readable format like CSV or XLS for cargo operations (may include some flight numbers representing truck or railway connections):  
_(in alphabetic order)_

  - [American Airlines Cargo](https://www.aacargo.com/ship/schedules.html);
  - [IndiGo Airlines](https://www.goindigo.in/information/flight-schedule.html);
  - [ITA Airways](https://www.ita-airways-cargo.com/s/flight-schedules?language=it);
  - [Lufthansa Cargo](https://lufthansa-cargo.com/de/network/schedule-routings);
  - [Singapore Airlines Cargo](https://www.siacargo.com/download_timetable.asp);
  - [SpiceJet](https://corporate.spicejet.com/schedules.aspx);
  - [United Cargo](https://www.unitedcargo.com/en/us/book/schedules.html);

## <i class="fas fa-subway"></i> Miscellaneous transportation data

_(in alphabetic order)_

- Brazilian [National Civil Aviation Agency](https://www.gov.br/anac/en?set_language=en)  
  with an [Open Data portal](https://www.anac.gov.br/acesso-a-informacao/dados-abertos/areas-de-atuacao/todos-os-dados-abertos) including historical, [current](https://siros.anac.gov.br/siros/registros/diario/diario.csv) and [future](https://siros.anac.gov.br/siros/registros/futuro/futuro.csv) flight schedules (in Portuguese)
- French [Transport Data National Access Point](https://transport.data.gouv.fr/)  
  with few data sources related to [aviation](https://transport.data.gouv.fr/datasets?type=air-transport) (in French)
- Japanese [Public Transportation Open Data Center](https://www.odpt.org/)  
  with a specific focus on [air transportation data](https://ckan.odpt.org/dataset?tags=%E8%88%AA%E7%A9%BA) (in Japanese)
