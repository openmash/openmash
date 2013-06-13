openmash
========

OpenMash is a documentation repository for the VA Scheduling 
Challenge submission. All other openmash sub-projects are part 
of the submission and are licensed under the Apache 
License version 2.0 (ALv2). These projects may depend on other 
open source projects licensed under the same terms as ALv2.
Please check the LICENSE and NOTICE files for each sub-project.

The supbrojects are:

* [Medshpere tests](https://github.com/openmash/medsphere-test) - 
automated tests for the challenge scenarios using the 
Medshpere Scheduling front-end.

* [Camel VistA](https://github.com/openmash/camel-vista) - 
Java Based mediation of VistA native RPC broker messages 
using [Apache Camel](http://camel.apache.org)

* Apache [Platform](https://github.com/openmash/apache-platform) - 
Apache Maven parent project used by other sub-projects.

* [VistA HL7](https://github.com/openmash/vista-hl7) - 
Java Based mediation of VistA HL7 messages using 
[Apache Camel](http://camel.apache.org) (uses the Apache 
Platform project)

* [Cosmo](https://github.com/openmash/cosmo) - ALv2 iCal 
and CalDav Based Calendar server

* [Saturn](https://github.com/openmash/saturn) web based 
scheduling front-end for Cosmo (similar to Google Calendar) 
that can be deployed in local environments (as an alternative to SaaS).

* [Syncope/Google/Saturn Demo](https://github.com/openmash/syncope-google-saturn-demo) - 
demo project demonstrating the integration of the Saturn scheduling front-end 
with the [Apache Syncope](http://syncope.apache.org) identity management project and Google apps.

* Calendar [Fixture Generator](https://github.com/openmash/calendar-fixture-generator) - 
tool to aid testing of the OpenMash Saturn calendar front-end.

* Scheduling [mesh-up](https://github.com/openmash/mashmesh) with 
Google Maps and Google Calendar or Cosmo
