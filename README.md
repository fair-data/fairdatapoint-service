# FAIR Data Point (FDP) Service

Docker compose files to deploy FDP service.

## Steps to deploy FDP service:

### Update the file `docker-compose.prod.yml`:

Replace the `YOUR_FDP_HOST_OR_SERVERNAME`,`YOUR_FDP_PORT` and `YOUR_GRLC_SERVER_NAME` in the file
with proper values. Check the exmaple values in `docker-compose.prod.example.yml`.

### Run docker compose to start the service:

Run the command:
```
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up
```
If you are using example values, you can then go to http://0.0.0.0 and http://0.0.0.0:8088/api-local to try the services.
