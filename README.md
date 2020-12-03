# TICK-Env
Boilerplate TICK (Telegraf, InfluxDB, Chronograf and Kapacitor) stack docker config for my home IoT projects.

## Deployment
Clone the environment to a local directory and deploy using docker swarm with the commands below
```
docker swarm init
docker stack deploy -c tick.yml
```
Modify telegraf.conf to include any necessary API keys
