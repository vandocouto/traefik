Step 1 - UP Traefik
<pre>
docker stack deploy --compose-file traefik.docker-compose.yml up
</pre>
Step 2 - Deploy Container Nginx - Traefik http/https
<pre>
docker stack deploy --compose-file nginx.docker-compose.yml up
</pre>