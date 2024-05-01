DuckDNS allow use dynamic DNS server.

# Setup the domain
At https://www.duckdns.org/ you can get a new domain and the token.

The docker-compose expects a `/duck_token.txt` plain text file with the token.

# Launch the container
The docker-compose.yaml file contains all the required configuration.
The container will automatically restart in all the host os shutdowns/restarts.

````bash
#launch the container in detached mode:
docker-compose up -d
````

