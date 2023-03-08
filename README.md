# Earthquake Hub Relocation Analysis 

## Introduction
Natural disasters like earthquakes can overwhelm local resources such as hospitals, medical services, and transportation, leaving many victims without the aid they need. In the aftermath of a major earthquake, bottlenecks in logistics can further complicate emergency response efforts. The objective of this project is to examine earthquake activity worldwide and identify the best locations to establish "resource hubs" that can be easily accessed by non-profit disaster relief organizations like The Red Cross and Direct Relief. By mapping earthquake data and analyzing logistical factors, this project aims to help these organizations be better prepared and respond more effectively in the event of an earthquake.

Feel free to check out this [interactive earthquake visual](https://public.tableau.com/app/profile/josephmsmith/viz/WWE_Visualizations/Final) created in conjunction with the presentation

## Purpose
Are the best locations for resource hubs located near the most active earthquake sites? What neighboring locations can be safe locations for these hubs?

## Data Sources
The primary data set is from the [USGS Earthquake](https://earthquake.usgs.gov/earthquakes/search/) catalog and contains information from all earthquakes worldwide from 2000-2003 with a magnitude of 2.5 or higher. This data set is 23 columns wide and ~614,000 rows long, begins in January 2000, and is up to date until February 2023. Based on the “Story of One Row” we can see all the general information regarding each individual earthquake such as time, location, and magnitude while also being able to access more thorough information such as depth, gap, type, etc. For the purposes of this analysis - time, location,  and magnitude are going to be the key columns for insight given the lack of geological analyzing we will be looking at. These are vital for the analysis as they not only provide information for where earthquakes are happening, but more importantly where they aren’t. By looking at zones that are far away from highly active earthquake areas we can build hubs most effectively. 

Limitations:
- Unknown locations of any currently used resource hubs
- Not all organizations respond to disasters in all countries

Assumptions:
- Organizations will work with local government to coordinate logistics
- Organizations involved will want to partner together

Secondary sources which focus primarily on research include but not limited to: [American Red Cross](https://www.redcross.org/about-us/our-work/international-services.html), [US Department of Interior](https://www.doi.gov/recovery#:~:text=When%20a%20disaster%20is%20declared,jurisdictions%20impacted%20by%20a%20disaster.), [FEMA](https://www.fema.gov/partnerships), [Direct Relief](https://www.directrelief.org/work/fundamentals-emergency-response/#:~:text=an%20emergency%20setting.-,Search%2Dand%2Drescue%20and%20emergency%20medical%20services%20come%20first.,officers%20are%20the%20first%20responders.)

## Analysis
The key questions for analysis are as follows:
- What are the most frequently affected Earthquake zones?
- Are there any trends for places that are becoming more active? 
- What do trends look like for most dangerous earthquake zones?
- What defines a good place to put a resource hub? 
- What are possible limitations for storing these resources?

The Process:
1. Identification of and segmentation of earthquake zones
2. Identification and mapping of safe zones and US allied territories
3. Routing, distance calculation, and accessibility analysis to most dangerous zones

