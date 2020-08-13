# ohw20-proj-ooi-profiles-section
OceanHackWeek 2020 project using OOI Pioneer Array CTD profiles to create section through shelfbreak front

GitHub: https://github.com/oceanhackweek/ohw20-proj-ooi-profiles-section

Please see the wiki page for links to data and example notebooks that we can use in this project

# Project 1: Visualizing an invisible boundary: locating the shelfbreak front in the northern Mid-Atlantic Bight

## Mentors
Stace Beaulieu, Woods Hole Oceanographic Institution, Information Manager for Northeast U.S. Shelf Long-Term Ecological Research (NES-LTER) (https://nes-lter.whoi.edu/)

James Munroe, Memorial University of Newfoundland

## Specific tasks

Note that in the limited time during the 2020 OHW, our hope is to be able to:
- Adopt script/notebook to access and plot OOI Pioneer profiler mooring CTD profile data
- Adopt script/notebook to plot a 2-D “slice” through the water column using multiple profiles (e.g., a vertical section contour plot of salinity) (e.g., https://www.researchgate.net/figure/Cross-shelf-transects-of-salinity-left-panels-and-temperature-right-panels-from-the_fig4_323491603)
- Document our notebook so that scientists and students who are not familiar with NetCDF data format (e.g., LTER ecologists) can generate a contour plot.

Further development beyond 2020 OHW would include:
- Develop and share a flexible notebook to “locate” the shelfbreak front in the "slice"
- Develop and share an animation to visualize the dynamic movement of this invisible boundary.

## The problem: What oceanographic data science problem are you going to explore?
The U.S. Ocean Observatories Initiative (OOI) provides data from moorings deployed in the Pioneer Array on the edge of the Northeast U.S. Shelf (NES) in the northern Mid-Atlantic Bight. Profiler moorings support wire-following profiling packages with a multidisciplinary sensor suite including temperature, conductivity (salinity), pressure (depth) and more. Although it may be straightforward to acquire and plot data from a single profile, or a single profiler over time, it is much more challenging to be able to visualize and analyze data from multiple profiler moorings. The goal of this project will be to develop flexible, scalable tools to assemble, plot, and analyze data from multiple moorings over time.

## Application Example
We are targeting a specific use case: locating the shelfbreak front and illustrating the dynamic movement of this invisible boundary. We would like to develop a flexible, scalable workflow implemented in a Jupyter Notebook to visualize and analyze CTD data (in particular, salinity and depth) from multiple profiler moorings. This use case will serve ocean scientists and students including those involved with NES-LTER.

## Proposed methods/tools
Python (packages including numpy, xarray, matplotlib, pandas), GitHub, Jupyter Notebooks, NetCDF data format, https://oceanobservatories.org/data/
