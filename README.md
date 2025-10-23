# manifesto


a frugal plain text html website to share projects, experiences, and beliefs.

## intent


I aim to share my projects, experiences, beliefs and more with this website.

## process


the process of writing and deploying this website reflects its content: simplicity and efficiency, which are principles I highly value.

#### architecture

the server is hosted on an oracle cloud instance but will be self hosted in the future. it contains :  
- a very basic nginx http server that serves static content, with a ssl certificate signed by certbot. the nginx server is containerized with docker and ran with docker compose. the application is deployed on the host with ansible.
