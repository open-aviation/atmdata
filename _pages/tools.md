---
layout: basic
title: Tools
permalink: /tools/
---

The following open-source software are freely available for all. These are precious tools for any ATM researcher.

---

## BlueSky, an open air traffic simulator

BlueSky is an open air traffic simulator provided for anybody who wants to visualize, analyze or simulate air traffic. It is commonly used to perform research on Air Traffic Management and Air Traffic Flows.

J. M. Hoekstra and J. Ellerbroek,  
"BlueSky ATC Simulator Project: an Open Data and Open Source Approach",  
*Proceedings of the 7th International Conference for Research on Air Transport*, 2016.

<https://github.com/TUDelft-CNS-ATM/bluesky>  
GNU General Public License v3.0  

---

## pyModeS, a decoder for ADS-B and Mode-S downlink messages

<img src="https://img.shields.io/badge/doi-10.1109/TITS.2019.2914770-brightgreen"/>

pyModeS is a Python library designed to decode Mode-S (including ADS-B) message.  
It can be imported to your python project or be used as a standalone tool to view and save live traffic data.

J. Sun and H. Vû and J. Ellerbroek and J. M. Hoekstra,  
"pyModeS: Decoding Mode-S Surveillance Data for Open Air Transportation Research",  
*IEEE Transactions on Intelligent Transportation Systems*, 2019  

<https://github.com/junzis/pyModeS>  
<http://pymodes.readthedocs.io>  
GNU General Public License v3.0

---

## traffic, a toolbox for processing and analysing air traffic data

<img src="https://img.shields.io/badge/doi-10.21105/joss.01518-brightgreen"/>

The traffic library helps working with common sources of air traffic data.

Its main purpose is to offer basic cumbersome data analysis methods commonly applied to trajectories and ATC sectors. When a specific function is not provided, the access to the underlying structure is direct, through an attribute pointing to a pandas dataframe.

The library also offers facilities to parse and/or access traffic data from open sources of ADS-B traffic like the OpenSky Network or Eurocontrol DDR files. It is designed to be easily extendable to other sources of data.

Static visualisation (images) exports are accessible via Matplotlib/Cartopy. More dynamic visualisation frameworks are easily accessible in Jupyter environments with ipyleaflet and altair; or through exports to other formats, including CesiumJS or Google Earth.

Xavier Olive,  
"traffic, a toolbox for processing and analysing air traffic data",  
*Journal of Open Source Software*, 2019  

<https://github.com/xoolive/traffic>  
<https://traffic-viz.github.io/>  
MIT License
