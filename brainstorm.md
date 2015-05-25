# WebAPI Meetup
* http://www.meetup.com/webapi-hamburg/
* May 27 - 6:30 PM - XING

# Internal API usage at wer liefert was
* Introduction on the development of the microservice architecture.
* Details of the design and usage of the internal API.
* Learnings gathered on the way.

# Structure
* Introduce Me
* Introduce WLW
* Where is WLW coming from
  * Printing books
  * Moving to an Web-Application
  * Growing the Monolith Rails (LOC ???)
* Moving to a Microservice Architecture
  * within 6 month
  * Now with ?? Rails Apps
  * Communication over APIs and AMQP
  * SAP System part of it
* The birth of a new environment
  * Guide the Heroku API guide
  * The Details we will learn on the journey
  * Only internal APIs for now
* JSON-Format
* Namespace
  * /interal_api/*
  * Easy to secure
* Versioning
  * example
* Pagination
  * example
* Fields
  * required
  * performance is stable when new expensive fields are added
* Error Handling
  * format
* Filter Methods
  * not over REST
  * url parameters
* Actions
  * resource/actions/blubber
* Documentation
  * First in confluence
  * Moved to the code repos
  * In the future swagger
* Library Support
  * API gem with convience methods
  * Already Version 5 in semantic Versioning
  * Server and Client
  * Raising and handling Errors
  * Test Helpers (build in vs. helper methods)
  * Special handling for SAP APIs (xml, no verion header...)
