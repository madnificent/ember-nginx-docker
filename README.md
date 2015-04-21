# ember-nginx-docker
Docker configuration for hosting standalone apps built by ember-cli

# example usage

``
   docker run -d \
          -p 8080:80 \
          --volume /path/to/ember/dist/folder:/app \
          --link my_backend_api_docker_name:backend
          madnificent/ember-nginx
``
