# CyProAssist connect

This page collects method that help to connect different software systems and/or devices within a typical CyProAssist application.

## [Message Queuing](https://en.wikipedia.org/wiki/Message_queue)

A form of asynchronous communiction between multiple threads within the same process or between multiple parties on different machines.

A lightweight protocol is [MQTT](http://mqtt.org/) that can be easily implemented with [Eclipse Paho](http://www.eclipse.org/paho/) clients and
the [Mosquitto](http://projects.eclipse.org/projects/technology.mosquitto) server.

## REST-style communication

### Linked Data Platform (LDP)

The [Linked Data Platform](https://www.w3.org/TR/ldp/) builds on the [Resource Description Framework (RDF)](http://www.w3.org/TR/rdf11-concepts/) and 
HTTP REST web services.

#### Pros
- single protocol and interfaces specification for access to objects in any system
- read and write access
- simple implementation and semantics

#### Cons
- no capabilities for searching
- may not be well suited for time series data (process and machine data)

### OSLC

An interface specification that was mainly developed to connect tools for software lifecycle management by using linked data principles. OSLC v3 is now an extension of LDP.

An interesting concept of OSLC are [Delegated Dialogs](https://tools.oasis-open.org/version-control/svn/oslc-core/trunk/specs/dialogs.html) that allow for embedding of foreign UI components for the creation or selection of resources that are contained within external software systems.

### Constrained Application Protocol (CoAP)

A binary protocol as compact alternative to HTTP for REST-style access to sensor data. 
