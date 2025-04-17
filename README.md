# ReepackOnt

This is an ontology used to standardize data coming from the _Reepack_ company in the context of the **DESIGN-IT** project. It is not intended to be used in other real-world scenarios.

Its classes are adapted from classes taken from:

- different **IOF** ontologies, namely the _Core_ ontology and the _SupplyChain_ ontology; from here, we are importing concepts related to industrial and manufacturing activities.
- the **SDW-SOSA-SSN** ontology, the result of a collaboration between **W3C** and **OGC**, modelling data for the **Spatial Data on the Web Working Group**; from here, we are importing the concepts related to sensors.

We added a single concept completely from scratch: `FoldingBox` &mdash; as a subclass of one of the imported classes &mdash; to prove that one can extend previously formalized knowledge to adhere to his/her own needs.
