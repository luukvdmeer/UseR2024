# Analyzing real-world geospatial networks in R

Presentation at the UseR! Conference 2024 in Salzburg, Austria. See below for the slides and for a Quarto notebook containing the presented code.

- [Slides](https://docs.google.com/presentation/d/1681pHOVNJG7n_x8U-VlZnxDBo5L3vb2X2C4uXAdkl0w/edit?usp=sharing)
- [Notebook](https://luukvdmeer.github.io/UseR2024/notebook.html)

## Abstract
Geospatial networks are graphs embedded in geographical space. They can be used to represent, analyze and model a variety of real-world complex systems. A motivating example is urban transport systems with their ongoing transition towards a sustainable design and increased focus on active travel. Streets, their surroundings, and their interconnections form the geospatial network. The analysis often involves an assessment of transport accessibility: how well does the network connect people to the places they want to go to? This talk will cover three main stages of such an analysis, and its implementation in R. First, we show how to import street geometries and amenity datasets from OpenStreetMap, using the package `osmdata`. Second, we show how to build a clean and routable street network from these data, using the package `sfnetworks`. Finally, we give an example of how to compute bicycle accessibility to different amenities, taking into account the suitability of the network for cycling. Although we focus on the application domain of transport planning, the content is meant to be useful for anyone interested in analyzing real-world geospatial networks in R.
