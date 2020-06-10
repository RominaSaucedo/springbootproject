# springbootproject
Backend Task – For Java Lead Candidate

Deliverables:
·Send us either a zip file  or a link to the new repo on GitHub.

Using:
·Spring Boot
·Embedded Tomcat

Task:
·A REST controller with individual services for:
·Adds a User to the list of stored users using a JSON request body. The request should be rejected if the same first name/last name combination is already stored in the system.
·Returns a single User when requested by ID as JSON
·Returns a list of all Users as JSON, ordered alphabetically by last name
·Deletes a User when requested by ID
·User object includes ID, first name, and, last name
·Store user using the h2 embedded database.
·Protect endpoints with Spring Security.

Bonus
·Appropriate HTTP status codes
