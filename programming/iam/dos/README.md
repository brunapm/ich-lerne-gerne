# Denial of Service
#### Also DDoS (Distributed Denial of Service)

A malicious attack that attempts to overload a server with requests, resulting in unavailability of response for the users.

DDoS also performs the flood of requests, but distributed in many devices.

It's possible to mitigate an attack by:
* Analyzing the requests and blocking IPs that appear malicious
* Rate limiting - restricting maximum of requests per a certain amount of time
* Upstream filtering - stop attacks from reaching the API or server by blocking them in other layers of communication
* Programming for Scale - when designing a system, it's important to consider the maximum number of requests and to be able to easily increase this number if it becomes necessary