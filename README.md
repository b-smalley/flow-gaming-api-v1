# Flow Gaming API v1
This was the first version of the REST API for Flow Gaming
The api has been moved to API v2(Still in beta) which replaces the basic Express.js routing with GraphQL and MySQL is replaced with MongoDB although v1 is still accessible for now

# Authentication
The request sender must include a cookie with the name id and the value of the request senders personal account id
AKA The request sender must log into the website to get thier uniqueid attached to them

# Getting User Data

## Getting an email address
GET: api.flowgaming.org/users/USERNAME/email
## Getting the request senders info
GET: api.flowgaming.org/myInfo/

# Updating User Data
## Updating a users email address
PUT: api.flowgaming.org/users/USERNAME/email/NEW_EMAIL'
