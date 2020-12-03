# TICK-Env
TICK (Telegraf, InfluxDB, Chronograf and Kapacitor) stack for my home IoT projects.

## Deployment
Clone the environment to a local directory and deploy using docker swarm with the commands below
```
docker swarm init
docker stack deploy -c tick.yml
```
