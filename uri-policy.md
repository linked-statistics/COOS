# COOS - Core Ontology for Official Statistics - URI and naming Policy

This document contains rules and guidelines for the identification and naming of the RDF resources associated to the Core Ontology for Official Statistics (COOS).


## General rules

The following rules apply for the identification of all COOS constructs:

  * All COOS components are identified by URIs using US-ASCII characters (no percent-encoding, no IRIs)
  * All the artifacts defined by the ontology have URIs starting with ```http://id.unece.org/```.
  * American English spelling is used (e. g. "organization ")


## OWL classes and properties

COOS uses the "hash URI" pattern for classes and properties:

  * The ontology URI is ```http://id.unece.org/def/coos```
  * All OWL classes and properties URIs add a fragment part, so URIs start with ```http://id.unece.org/def/coos#```

Regarding the fragment part, COOS uses:

  * Upper camel case for classes, for example ```StatisticalActivity```
  * Lower camel case for properties, for example ```supports```

Note that non-alphanumeric characters are ignored when camel casing expressions, for example ```SubProcess```.


## Instances

Instance resources URIs generally conform to the following structure:

```http://id.unece.org/{domain}/[{type}/]{identifier}```

  * ```domain``` denotes the business domain relevant for the resource, for example: activities, products, organizations, etc.
  * ```type``` corresponds to the most specific class of which the resource is an instance. 
  * ```identifier``` distinguishes unambiguously the instance in the context defined by the domain and type.

```domain```, ```type```   and ```identifier``` use lower camel case (all letters of an acronym use the same case).

Examples:

  * ```http://id.unece.org/activity/subProcess/6.3``` is the URI of the GSBPM sub-process 6.3 ("Interpret and explain outputs")
  * ```http://id.unece.org/activity/activity/3.7``` is the URI of the GAMSO activity 3.7 ("Manage Finances")
 
The following specificities apply:

  * When the resource is well-known enough in the ```domain``` context, the ```type``` part can be omitted: ```http://id.unece.org/activity/gamso```
  * When no standard identifier exist, a pseudo identifier will be constructed from the usual name: ```http://id.unece.org/activity/officialStatistics```
  * Acronyms can be used for the ```type``` segment when there is no ambiguity: ```http://id.unece.org/organization/nsi/gus```


## Notes

  * URI policy enforcement and management should be part of the COOS governance.
  * Use of plural for domains (activities, organizations...) would avoid confusion and redundancy: ```http://id.unece.org/activities/activity/3.7```
