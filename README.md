# Test Description

## Introduction

Snowman Labs is developing an application that allows the users to view and create tour points on a map. You need to create a cloud service applications to consume and register this information in mobile app.

## Goal

Develop a webservice for the mobile app.

## Non-functional rules

* RESTful based architecture;
* The developer can choose your favorite database, but it must be free and relational;
* Python development mandatory;
* Using the Django Framework, in the latest version available;
* The developer can use Docker, Redis and Elasticsearch if necessary;
* The developer must deal with all the requisition structure and data security.

## User Stories

* As an user, I want to signup using my facebook account;
* As an user, I want to signin using facebook
* As an user, I want to view a tour points list in a 5km radius from my actual position;
* As an user, I want to register a tour point with a name, geographical coordinate, category and set public or private register;
* As an user, I want to view a list tour points I registered;
* As an user, I want to delete a tour point I registered.
* The categories of the presentation will be fixed in the follow ones:

  * Park;
  * Museum;
  * Restaurant;

* An anonymous user can only see the tour points for restaurant category;

## Deliverables

See bellow the following deliverables:

* Source code in public git repository (Github or Bitbucket);
* Instructions for running and configuring the code.

## Evaluation

The evaluation will follow the criterias below:

* Good practices;
* Source code maintenance;
* Performance;
* Data security;
* Data consistency;
* Organization;
* Full operation;
* Confiability;
* Robustness.

## Bonus

* If there is cache: done with libraries;
* Use of unit tests
* Postman file with all configured methods