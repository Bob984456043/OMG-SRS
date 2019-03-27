Non-functional Requirements
===========================
    We will explain some non-functional requirements to achieve 
    a better user experience.

Response Time
-------------
    Because this network application is used by biologists all over 
    the world, the server may have to bear a lot of requests, which 
    may lead to some problems, such as system downtime several times 
    or loss of response to customers.
    On the other hand, if users have a large amount of data to analyze, 
    then time complexity must be considered. For optimization, our algorithm 
    should deal with this situation sufficiently effectively.
    After discussion, we have decided on the limit of response time, 
    which should be less than 5 seconds for most use cases.


Aesthetic Aspects
-----------------
    As a web application to solve biological analyzing. The interface 
    should be designed as simply as possible and make the scatter plot 
    and table more distinct.


Confidentiality Policy
----------------------
    Data security must be considered. For biologists, every 
    experimental result is an important achievement. Web 
    applications must maintain the reliability, integration and 
    confidentiality of experimental data, and experimental data 
    should not be disclosed without the consent of the owner.
