# Overview



The Possession System is the core gameplay mechanic, it allows the ghost to leave its current body and use any corpse as its new body.



This ability is not restricted by distance nor is it limited by a consumable resource, shifting the focus onto traversing the world using a network of corpses and using different identities as a social engineering tool.







\# Architecture



This system is divided into the following responsibilities:



\## Client Possession

&#x09;Handles corpse selection and possession effects



\## Server Possession 

&#x09;Handles possession requests and execution



\## Round Manager

&#x09;Maintains death state, restores playable characters and replicates death updates



\## Create-Corpse Module

&#x09;Creates ragdoll corpses



The following diagram illustrates the relationship between these components.



!\[Possession Architecture](possession\_architecture.drawio.svg)





































&#x20;

