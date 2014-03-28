## whoami

Jeff Beck

TechLead at ReachLocal
~~~~
## What I mean by MicroService

  * Single concern 
  * Deployable in isolation

~~~~
## Our Architecture

Over the course of acuasitions and expanding the products we have come out with a polyglot architecture including Java, Groovy, Ruby, PHP, Node, and PERL. In order to take advantage of our exsisting talent and software, we have started down the micro-service path.

~~

//TODO INSERT PIC

~~~~
## Where Grails Fits

  * REST Resources
  * GORM

~~
## Where Grails Doesn't Fit  

  * Batch Jobs
  * Lacking any web endpoint

~~~~
## Subscription Service

Acts as the source of truth about subscriptions.

  * Exposes the Subscription REST Resource
  * Emminates Events

~~
## Requirements

  * Application Monitoring
  * Security
  * Server Setup
  * Builds
  * Deployments

~~~~
## Building our Service

All our Grails micro services start out the same way. 

~~
### Project Setup

  * Grails create-app 
  * Change Java Version to 1.7
  * Standard Forked Mode Settings
  * Add Internal Nexus 

~~
### Plugin Setup

  * Add our normal plugins
  * Remove the extra standard plugins
  * Set up cucumber
  * Configure GORM

~~
### Build and Repo Setup

  * Commit everything as the starting point
  * Add the new CI job
  * Bring up a dev server

~~~~
## Customizing our Service

