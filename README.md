# Final project of the AI Builder course - Uni Helsinki

# Summary
> Name your project and prepare to describe it briefly.

'AV Route Optimisation' of an autonomous vehicle in a city area disconnected to public transport.

To bring passengers of a city area, which is isconnected to public transport, to public transport locations and back home.
It is the target to optimise travelling time of passengers and overall distance travelled of the AV.

# Background
> What is the problem your idea will solve? How common or frequent is this problem? What is your personal motivation? Why is this topic > important or interesting?

An automous vehicle is driving around a confined city area to pick up residents from their homes to bring them to a fixed number of destinations. The fixed destinations are bus stops, train station, public pick up places. 
The residents can also travel back from the fixed locations to their homes.

The autonomous vehicle covers the last mile to home and is moving continously. The AV tries to permanently optimise its route based on experiences from past routes and calls from passengers. The passengers are using an app which allows them to submit a call from their current locstion to one of the fixed locationns or from one of  the  fixed locations to their home. Pick up points from homelocations are predetermined and fixed.

The route optimisation would lead ultimately to cost savings and less energy consumption. 



# Data and AI techniques: 
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


# How is it used: 
> What is the context in which your solution is used, and by whom? Who are the people affected by it? It’s important to appreciate the
> viewpoints of all those affected.

Residents of a fairly remote city area not well connected to the public transport system will use the AV to reach a public transport location or reach home from the public transport location.

Parties involved:
* passengers
* bus operator
* city planners


# Challenges

> What does your project not solve? It’s important to understand that any technological solution will have its limitations.
> What next: How could your project grow and become something even more?

Target would be to achieve an optimal travelling time for each passenger (direct route) but this is not possible as many passengers have to be served.


# Acknowledgments: 
> If you’re using open source code or documents in your project, make sure you give credit to the creators. Mention your sources of
> inspiration, too.

So far not used any references.

