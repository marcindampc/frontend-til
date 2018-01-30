port HTTP -> 80

# HTTP methods
* GET
* HEAD
* POST
* PUT
* PATCH
* DELETE
* OPTIONS
* TRACE
* CONNECT

# cookies
* user side data
* data send as header in HTTP Request
* easy to read from user device
* easy to modify/delete by user
* max 4KB
* data store as text (i.e. JSON)

# session
* server side data
* only id/token is send in HTTP Request
* needs solid infrastructure to work properly
* posibility of token stealing

# LocalStorage (10MB) & SessionStorage (5MB)
* user side
* nothing is send to server
* easy to read from user device
* can be modify/delete by user
* Local is unexpiring
* Session is attached to 1 tab
* Session is cleared when window (tab) is closed
* data store as text (i.e. JSON)

port HTTPS -> 443
* more complicated
* more network resources needed
* sniff-proof

# authorization types
* basic (fragile; needs SSL (Source Socket Layer) or now TSL (Transport SL))
* digest (prone for man-in-the-middle)
