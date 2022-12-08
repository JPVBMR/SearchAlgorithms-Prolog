# Prolog - Artificial Inteligence Project


## Project Objectives

- In this project it's intended to build a system of representation of knowledge and
reasoning capable of characterizing a universe of discourse in the logistics on the
distribution of orders, among other objects. Living in times where
ecology is a very relevant topic in our society, the company Eco Delivery has
with the aim of always favoring the most ecological means of delivery. The company has
2 out of 4 various means of transport: bicycles, motorbikes and cars, which can be
classified by ecological aspect.

- An Eco Delivery courier, in the context of a city, has associated a set of
deliveries to be made on certain streets of a city, which are associated with the
corresponding parish. Each customer will be able to indicate the maximum time
in which you want your order to be delivered, thus existing delivery times
(immediate, 2h, 6h, 1 day, etc). If the courier does not meet the deadline set for the
delivery of the order will suffer a penalty, such as, for example, the reduction of
deliveries associated with you. It should also be possible for the customer to classify the
courier delivery, in a ranking between 0 and 5 stars. Each order to be distributed
must be characterized at least by its weight and volume. The service price of
delivery must take into account, in addition to the order, at least the delivery time
and means of transport used

- The elaboration of the practical case should also take into account some aspects:
  - Bicycles can transport packages up to a maximum of 5 kg, taking into account
    counts an average speed of 10km/h;
  - In the case of motorcycles, this means can transport orders with a limit
    maximum of 20 Kg and with an average speed of around 35km/h;
  - Relative to the car, this will have an average speed of approximately
    25km/h, with a maximum transport weight of 100kg.
  
- From this characterization and to carry out the work, the group should build
  a practical case, which is capable of demonstrating the functionalities underlying the
  use of the logic programming language PROLOG, within the representation
  of knowledge and construction of reasoning mechanisms for the resolution of
  problems.
 
- The elaboration of the practical case should respect the needs of
  demonstration of at least the following functionalities:
  - identify the courier who most often used a more expensive means of transport
    ecological (e.g., bicycle, motorbike, car);
  - identify which couriers delivered certain order(s) to a
    particular customer;
  - calculate the number of deliveries by Eco Delivery in a given
    period;
  - identify which areas (e.g., street or parish) have the highest volume of
    deliveries by Eco Delivery and courier;
  - calculate the average customer satisfaction rating for a
    certain messenger.

>**Note** They should create a minimally realistic scenario where deliveries will be made (e.g.,,
a city), using the most appropriate representation for this purpose. The delivery points for orders should be covered by the scenario developed
previously.

- Each delivery circuit is divided into the following elementary considerations:
  - Initial State – delivery point, particularly in the center of the Eco Delivery distribution;
  - Delivery Points – Route between two delivery points of orders;
  - Final State – Return to the Eco Delivery distribution center.
  
- The elaboration of the practical case should also allow, taking into account the location of the
starting point (the distribution center), among other issues:
  - Generate delivery circuits, if any, that cover a certain
  territory (e.g. street or parish);
  - Representation of the various delivery points in the form of a graph, taking into account
  account that you should only have locations (streets and/or parish) available in the
  knowledge base;
  - Identify which circuits have the highest number of deliveries (by volume and weight);
  - Compare delivery circuits taking into account productivity indicators;
  - Choose the fastest route (using the distance criterion);
  - Choose an ecological circuit (using the time criterion).

- In the development of solutions for the elaboration of the practical case consider different
**search strategies (uninformed and informed)**.
  1. Formulation of the problem as a research problem indicating the
  representation of the initial (current) state, objective state/test, the operators
  (name, preconditions, effects) and solution cost;
  2. Search strategies that should be implemented:
    - The. **Uninformed Search**, explaining how it works, when it applies and
    what is the associated temporal and spatial complexity:
      - Depth (DFS - Depth-First Search);
      - Width (BFS - Breadth-First Search).
    
  - **Informed Search**, explaining how it works and how it is applied and which
was the heuristic used for the problem to be solved and why this
heuristic was chosen.
    - Greedy Search;
    - Star Search.


## Development Strategy


### Knowledge Base 



