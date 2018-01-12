# Activity 2 Submission
### Ryan Samarajeewa, Yuki Hayashi, Mohammed Abousaleh

## Mock-up
![Mockup](https://i.imgur.com/Ml8RZE5.jpg)

## Description
Outlined below is a description of our solution in terms of the "What, Why, How" framework.

### What

#### Datasets
* **Data Types**: 
  * Items: Departure time, Arrival time, Boat load
  * Links: Network consisting of vessel paths (edges) and ports
  * Positions: Current boat location; i.e. distance between the boat and berth
* **Data and Dataset Types**: 
  * Networks & Trees: Items(nodes) = ports, Links = vessel routes, Attributes = departure and arrival time
* **Dataset Types**: 
  * Tables: Docks will show a table contatining the departure and arrival time
  * Networks: As mentioned above, the majority of the display is consumed by a network of vessel paths and ports
* **Dataset Availability**: 
  * Dynamic: Position of the vessel and estimated arrival/departure time updates in real time. 

#### Attributes
* **Attribute Types**: 
  * Categorical: Dock and bearth location
* **Ordering Direction**: 
  * Diverging: Vessel position in a single route
  * Cyclic: The days of the week and the 24 hour span

### Why
#### Actions
* **Analyze**: 
  * Consume: This visualization can be used to disover and present all of the ongoing routes
* **Search**:
  * Lookup: Clicking on a vessel will show its load size and estimated arrival time. 
* **Query**:
  * Compare: Estimated departure and arrival tim can be compared to other days of the week.

#### Targets
* **All Data**:
  * Trends: Geting recent departure/arrival times will allow better predictions of future departure/arrival times. 
  * Outliers: If a delay in departure or arrival time occurs, it will be displayed in the docks or vessels.
* **Attributes**:
* **Network Data**:
* **Spatial Data**:

### How
* **Encode**: We will encode different data types into different aspects of the visualization. For example, the availabile capacity of each vessel will be encoded as a percentage shaded into the vessel itself that can be scanned quickly with the eyes.
* **Manipulate**: We will select the parts of the data we deem to be most important to highlight as the primary focus of the visualization. For example, the capacity of the vessels and their current locations will be immediately clear to the user, whereas further information such as departure and arrival times, as well as historic data, requires some interaction by the user to reveal.
* 


## Design Study Methodology 
Described below is how we would use the design study methodology for this task. Each stage may result in a revisitation of a previous stage with acquisition of new knowledge, realization of lack of knowledge, possibility for improvement, or requirements changes.

### Precondition Phase
* **Learn**: Because it is assumed that we hold sufficient expertise in the field of information visualization, we can skip this phase entirely at first. However, we may revisit this stage to acquire new knowledge if needed.
* **Winnow**: We assume that this collaboration is the most ideal, thus we can skip this stage.
* **Cast**: We assume that we have established the most ideal roles for collaborations, thus we can skip this stage.

### Core Phase
* **Discover**: We would obtain requirements from the initial problem description, and conduct further requirements gathering as the project progresses. 
* **Design**: A majority of the project timeline will be spent during this stage. After initial deployment, we may revisit this stage to make improvements. 
* **Implement**: Once an acceptable design (deemed by the design team and stakeholders, Seaspan) has been formed, implementation may begin. Throughout this stage, it is crucial that the stakeholders are kept in the loop in the case that requirements changes arise.
* **Deploy**: Once an acceptable implemetation has been developed, we would deploy the solution for production usage.

### Analysis Phase
Because this is a project in which a problem is defined, a solution is created, tested and deployed, we would not need to reach this phase entirely. 

## Study pitfalls to consider
