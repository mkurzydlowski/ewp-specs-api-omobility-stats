Outgoing Mobility Stats API
===========================

* [What is the status of this document?][statuses]
* [See the index of all other EWP Specifications][develhub]


Summary
-------

This API allows the client to get the statistics describing outgoing mobilities from the sending HEI.

If HEI provides any API from the following group:
* Outgoing Mobilities
* Outgoing Mobilities CNR
* Outgoing Mobilities Stats
* Incoming Mobilities
* Incoming Mobilities CNR

it MUST provide all APIs from this group.


Request method
--------------

* Requests MUST be made with HTTP GET method.


Other requirements
------------------

Refer to [this document][ewp-architecture] for more details about requirements for statistics endpoint.


Error handling
------------------------------

* General [error handling rules][error-handling] apply.

Response
--------

Servers MUST respond with a valid XML document described by the
[response.xsd](response.xsd) schema. See the schema annotations for
further information.


[develhub]: http://developers.erasmuswithoutpaper.eu/
[statuses]: https://github.com/erasmus-without-paper/ewp-specs-management#statuses
[error-handling]: https://github.com/erasmus-without-paper/ewp-specs-architecture#error-handling
[ewp-architecture]: https://github.com/erasmus-without-paper/ewp-specs-architecture#ewp-statistics