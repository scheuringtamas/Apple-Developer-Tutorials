# Earthquakes

This project is part of [iOS App Dev Tutorials](https://developer.apple.com/tutorials/app-dev-training/).

The United States Geological Survey (USGS) hosts a JSON feed of earthquake data. This module guides you through the development of Earthquakes, an iOS app that queries and presents this data.

## Earthquakes list
The list displays a navigation view that contains all the earthquakes in the feed. Users can delete individual earthquakes. Tapping the Reload button refreshes the feed and reloads the earthquakes.

## Earthquake details
The detail view shows more information about an earthquake, including a map of the region surrounding the earthquake. The app fetches and loads the coordinates for each earthquake on demand in the background when it displays the detail view.

## Earthquake data
The USGS data contains many details for earth scientists. As an app for the general population, Earthquakes ignores most of those details and extracts six common properties of each earthquake: the name of the location, time, magnitude, latitude, longitude, and detail. Together, the latitude and longitude make up the geographical coordinates.

## Network layer
Earthquakes relies on a network client to load the earthquake data. The client performs network transfers concurrently in the background, keeping the interface responsive.

## Screenshots
<img src="/iOS-App-Dev-Tutorials/Earthquakes/Screenshots/Earthquakes.gif" width="300"/>
