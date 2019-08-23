# Flow Gaming API v1
This was the first version of the REST API for Flow Gaming

# Authentication
The request sender must include a cookie with the name id and the value of the request senders personal account id cookie
AKA The request sender must log into the website to get thier uniqueid

# Getting User Data

## Getting an email address
GET: api.flowgaming.org/users/USERNAME/email
## Getting the request senders info
GET: api.flowgaming.org/myInfo/

# Updating User Data
## Updating a users email address
PUT: api.flowgaming.org/users/USERNAME/email/NEW_EMAIL'
