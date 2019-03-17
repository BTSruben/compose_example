# compose_example

Docker compose:

WEB ( Flask app) >> DB ( Redis )

Ports 

5000:5000

Curl commands:

POST:

curl --header "Content-Type: application/json" --request POST --data '{"name":"Ruben"}' localhost:5000

GET:

curl -i localhost:5000
