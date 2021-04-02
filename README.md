
# AV-Route Optimisation

A project submission for the Building AI course of the Uni Helsinki.


## Summary
> Name your project and prepare to describe it briefly.

Name: 'AV Route Optimisation' 

This project is about the route optimisation of autonomous buses circling and roaming around in a city area which is disconnected to public transport.

The autonomous buses bring passengers living in the  city area to various destinations in the area. Those destinations can be public transport stations, pick up points or other homes in the area.



## Background
> What is the problem your idea will solve? How common or frequent is this problem? What is your personal motivation? Why is this topic > important or interesting?
> 
The project improves public transport in a confined city area which is disconnected from the major public transport system (train, underground, etc)

Autonomous buses are driving around in the respective city area to pick up residents from their homes to bring them to a number of destinations in the area. The destinations can be bus stops, train station, public pick up places, other homes and otherv places of interest.

It is the target of the project to optimise travelling time of passengers and to minimize the overall distance travelled by the AVs.


The autonomous buses try to permanently optimise their routes based on passenger's destinations, experiences from past routes and calls from passengers. 

The passengers are using an app which allows them to submit a call from their current location to one of the registered locations in the area.

The route optimisation would lead ultimately to cost savings and reduced energy consumption. 



## Data and AI techniques: 
> What data sources does your project depend on? Almost all AI solutions depend on some data. The availability and quality of the data
> are essential. Which AI techniques do you think will be helpful? Depending on whether you've been doing the programming exercises or
> not, you may choose to include a concrete demo implemented by coding, using some actual data!

### Data
+ registered public and home locations
+ current position
+ historical routes 
+ performane in the past (time passengers spent in the bus vs optimal time)
+ map of the area
+ call
+ feedback from passenger and driver

### AI Methodologies
+ route optimisation
+ probabilities of passenger waiting at certain points
+ visualisation of passenger locations


## How is it used: 
> What is the context in which your solution is used, and by whom? Who are the people affected by it? It’s important to appreciate the
> viewpoints of all those affected.

Residents of a fairly remote city area not well connected to the public transport system will use the AV to reach a public transport location or reach home from the public transport location.

Parties involved:
* passengers
* bus operator
* city planners


## Challenges

> What does your project not solve? It’s important to understand that any technological solution will have its limitations.
> What next: How could your project grow and become something even more?

Target would be to achieve an optimal travelling time for each passenger (direct route) but this is not possible as many passengers have to be served.


## Acknowledgments: 
> If you’re using open source code or documents in your project, make sure you give credit to the creators. Mention your sources of
> inspiration, too.

So far not used any references.

