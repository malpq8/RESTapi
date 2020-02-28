# RESTful API documentation for "Documents" Entity.

## Show a single Document

**URL** : /api/Documents/:pk/

**URL Parameters** : pk=[integer] where pk(primary key) is the ID of the Document on the server.

**Calling Method** : GET

**Response Format** : JSON

## Create a Document

**URL** : /api/Documents/

**Data Constraints** : "name": [unicode 64 characters max]

**Calling Method** : POST

**Response Format** : JSON

## Update a Document

**URL** : /api/Documents/:pk/

**Data Constraints** : "name": [unicode 64 characters max]

**Calling Method** : PUT

**Response Format** : JSON

## Delete a Document

**URL** : /api/Documents/:pk/

**URL Parameters** : pk=[integer] where pk(primary key) is the ID of the Document on the server.

**Calling Method** : DELETE

**Response Format** : JSON








