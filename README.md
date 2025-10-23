# manifesto


a frugal plain text html website to share projects, experiences, and beliefs.

## intent


I aim to share my projects, experiences, beliefs and more with this website.

## process


the process of writting and deploying this website is, which reflects the content of the latter, illustrates efficacity and simplicity, which are principles I esteem highly.

#### architecture

the server is hosted on an oracle cloud instance but will be self hosted in the future. a very basic nginx http server that serves static content, with a ssl certificate signed by certbot. the nginx server is containerized with docker and ran with docker compose. the application is deployed on the host with ansible.
