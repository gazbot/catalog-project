## Udacity Project Catalog Application

Requirements

	Python 2.7
	Flask
	SQLAlchemy
	OAuth2Client
	
Launching the catalog from the base directory

	$ python ./application.py

Then point your browser to `http://localhost:8000/`


## API

The following API endpoints support JSON and XML requests

	/items/
	/items/<item_name>/
	/categories/
	/category/<category_name>/

To receive data in the desired format, you will need to specify the desired
content type in the http request sent with the 'Content-Type' parameter.

JSON Response example with cURL

	curl -H 'Content-Type: application/json' http://localhost:8000/items/

XML Response example with cURL

	curl -H 'Content-Type: text/xml' http://localhost:8000/categories/
