# Visualizing Ireland Crime Rate

![Image description](https://github.com/TheAdityaVishnu/VisulizingIrelandCrimeRate/blob/master/Map%20View.png)

![Image description](https://github.com/TheAdityaVishnu/VisulizingIrelandCrimeRate/blob/master/Analytic%20View.png)


The aim of the visualisation is to show the rates of different crime categories in various counties of
Ireland from 2010 to 2016 (from 2003 in some cases). It also shows the crime rate for each individual
garda station in those counties.

The data for this visualization was obtained from “All-Island Research Observatory” which maintains
the records for all the crime rates reported by Garda in various parts of Ireland [1]. The data set
consists of records of 13 different types of crime categories for every Garda station in Ireland.

This data visualisation was made in Tableau, the desktop edition. This visualization has 2 views in it.
In the ‘Map View’, you can see the map of Ireland with various filters (year, crime-category, county,
garda station). On hovering the map over a county, it shows the total crime rate for that county
including a breakdown of the statistics for all the 13 crime categories. Similarly, hovering the mouse
over a Garda Station, would show the crime statistic for only that individual station. Subsequently, in
the ‘Analytical View’, you can the various bar chart graphs comparing the various crime categories
and counties.

## Encoding

* Mark/Shape: Solid Circle are used to represent each Garda Station on the Ireland Map

* Position: The position of the circle is mapped to the latitude and longitude of every Garda Station.

* Color variation is being used for encoding the rate of crime:

* Color Green reflects more crime rate.

* Color Yellow reflects less crime rate.

* Various checklist filter options have been provided to show crime on the basis of year, crime-category, county, garda station.

## Tasks

* Depicting the various trends and patterns of rates of crime level in various counties of
Ireland.

* To be to find the county which has the most and least crime rate.

* To be to find the crime category which is more common in a particular county.
* Uncovering the garda stations in a county which has more crime rate to find the most
unsafe areas.

## Limitations
* You may visualize counties which are either safe or unsafe, however this visualization
doesn’t explicitly mention it subjectively.
