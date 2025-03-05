# Calgary-Transit-Analysis
This uncover insights that will be useful for Calgary Transit in optimizing its services and improving Calgary's overall connectivity. 

### Introduction

Public transport is essential for getting around in cities, offering an affordable and sustainable alternative to individual automobiles. In a city that is expanding quickly like Calgary, understanding transit patterns such as route popularity, stop locations, and trip efficiency - is crucial for optimizing service quality and satisfying the community's requirements. The objective of our project is to explore Calgary’s transit scheduling data through a thorough inspection of routes, trips, stops, and stop times. We will focus on transit density, route types, popular destinations, and service types to find patterns to help direct data-driven improvements to the transit system.

Our analysis will tackle questions about operational effectiveness and transit demand. We will determine the busiest routes, comprehending stop coverage for important locations like schools and hospitals. We will also evaluate the relationship between time and distance travelled. The overarching goal of this analysis is to uncover insights that will be useful for Calgary Transit in optimizing its services and improving Calgary's overall connectivity. The results may serve as the foundation for future projects to improve Calgary's accessibility and urban transit system.



To explore the selected datasets we have come up with the following research questions. More details about the datasets is provided in the next section.

1- How many routes are in the Calgary Transit system?

2- What are the different transit route types available (bus, ferry, train etc)? How are they distributed?

3- How many routes service multiple neighbourhoods (e.g. Huntington — Sunridge) and how many stay within a neighbourhood (e.g. Evanston)?

4- Which areas have more bus routes and which areas are underserved?

5- What are the trip distances and travel times of express routes (highways, airports, etc) compared to local routes?

6- What are the most popular routes on Calgary Transit?

7- How do the direction of a trip and destination impact bus trips?

8- Which day of the week is the busiest for Calgary Transit, and what are the diffirences between weekday and weekend use?

9- How many transit stops are there specifically for schools and hospitals in Calgary?

10- What is the average distance between consecutive stops?

11- What are the best 10 stops nearest to the given location(considering University of Calgary)?

12- Find the 10 stops with highest number of stops and with the highest duration

13- What is the shortest and longest trips?

14- What is the total distance travelled for each trip?

15- How does the total distance travelled for each trip compare to the total travel time?

### Datasets

The datasets for our project were retrieved from Calgary Transit, a mission-driven initiative that provides data and advocacy about transit in residential communities. The data is open for all, showing transparency in the government and innovation and reuse of the data by citizens and community-based organizations. These data sets can be downloaded at no charge from the City of Calgary’s Open Data Portal here, with use subject to the Open Government Licence — City of Calgary.

The datasets are in TXT format, enclosed in a zip file, and easy to process using Python and a database. At the time of the proposal, the Calgary transit data was last updated from the website on October 24, 2024. It contains 8 datasets, with data, metadata/data dictionary, and validation constraints provided according to the General Transit Feed Specification (GTFS):

Agency: Transit agencies with service represented in this dataset.

Calendar: Service dates specified using a weekly schedule with start and end dates.

Calendar Dates: Exceptions for the services defined in the calendar dataset

Stops: Stops where vehicles pick up or drop off riders.

Trips: Trips for each route. A trip is a sequence of two or more stops that occur during a specific time period.

Routes: Transit routes. A route is a group of trips that are displayed to riders as a single service.

Shapes: Rules for mapping vehicle travel paths, sometimes referred to as route alignments.

Stop Times: Times that a vehicle arrives at and departs from stops for each trip.

This analysis focuses primarily on the routes, trips, stops, and stop times datasets, with some secondary usage of the calendar dataset. There are relationships between these data as shown below.


