# docker-nginx-uwsgi-flask-node-react

Caveat: In order to simplify development, I've created a couple of shared volumes that map files from my development machine to the Docker container. In a production environment, generating the bundled HTML, CSS and JavaScript and configuring NGINX is handled by the `Dockerfile.nginx`.

## To-do
1. Use Docker environment file to configure containers;
1. Use template nginx configuration file and replace that inside the container so we can drop the shared volume;
## Running the application
1. Copy the pip configuration file:
`cp back/requirements.txt.dist back/requirements.txt`

2. Copy the node configuration file:
`cp front/packages.json.dist packages.json`


