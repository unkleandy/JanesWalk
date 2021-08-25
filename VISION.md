# Jane's Walk

## The Idea

Jane’s Walk are traditionally a community-based approach to city building that uses volunteer-led walking tours to make space for people to observe, reflect, share, question and re-imagine the places in which they live, work and play.  

These walks are guided by the pricipals of Jane Jacobs (1916-2006), a writer, urbanist and activist who championed the voices of everyday people in neighbourhood planning and city-building.  

This project seeks to provide a digital alternative that can be practiced all year round.  

## The Execution

The Jane's Walk project is meant to be a web site that uses an API as well as mobile application for Android and iOS. The API will be developped first, then the website and mobile apps.

### Modules

JanesWalk will use and develop Open Source modules.

### Architecture and Language

JanesWalk will initailly be a REST API the coding language is to be determined, but probably in Python/Django, just because I feel like it.  

### Creating a walk

Each walk has :

* a creator
* a name
* a path linking nodes of interest
* a series of nodes

Each node has:

* cardinal coordinates — or a street adress
* a story (text blurb or audio)
* one or more pictures

### Users

There are two types of users :  

* annonymous users
* general users
* maintainers

Annonymous user features :

* Viewing a walk

General user features:

* Same as annonymous +
* Login
* Creating/editing a walk
* Publishing a walk
* Having walk favorites

Maintainer features:  

* Login
* Approving or disappoving a walk
