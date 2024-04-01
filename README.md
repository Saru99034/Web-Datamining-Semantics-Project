# Web-Datamining-Semantics-Project

Project
Web datamining & semantics Project
The Semantic Web project is a large and long practical exercise that consists in integrating all the pieces that have been seen during the first sessions into a consolidated application. To make sure you can advance sufficiently fast to cover everything, you will work by pair.   

Main objectives

Design a food delivery discovery service : We will describe different kinds of entities that are useful for the food delivery discovery service: food products, offers for the food items (including a single item or combos), restaurants and businesses that offer the food items; delivery services (deliveryman, or company: Delivroo, Uber Eats, ...) that work with the restaurants and business to deliver their food items; customers with their customers’s preferences.
Develop an application that provide, given a customer’s description, the place where to order food at the time of request.
Pedagogical objectives

Do a little software development, using Semantic Web programming frameworks
Setup and interact with an RDF database
Exploit multiple sources of heterogeneous data
Present information online with rich metadata

Part I: Modeling the ontology

In this part, we aim to create an ontology, using the Protégé editor, which models the food delivery discovery schema in terms of classes hierarchy, properties and restrictions.  

Indications :

1) Define different class and propertie hiearchies (at leat three hiearchies and three restrictions)
2) Define different class restrictions (eg. disjoint, existential and universal restrictions and other conditions on defined classes, ...)  (at leat three)
3) Define at leat three different type  of the properties (transitive, symmetric, inverseOf, etc.) if necessary.
4) You application should follows the Linked Data principles:
    1) As a starting point, individuals are recommeded to be described as instances of classes in Schema.org  schemaorg.owl. For instance, food products, be instances of schema:Product; 
    2) User preferences with respect to location, time, price range and, optionally, type of food should be stored in the Linked Data Platform. An example of preferences is provided in the pref-charpenay resource.
    3) The data of the service should be available online and represented in a standard vocabulary that any application can process. 
5) Check the consistency of your ontology with PELLET

With the Github, we answered for this question :
The data of the service should be available online and represented in a standard vocabulary that any application can process. 

So we put our rdf file with all data in our github. You have access with our github link : 
https://github.com/Saru99034/Web-Datamining-Semantics-Project.git
