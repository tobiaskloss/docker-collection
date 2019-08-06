# docker-monitoring-env
A simple setup for a monitoring system based on docker. The environment can be setup using ansible, located in [this](https://github.com/tobiaskloss/monitoring-setup) repository.

Before use you will need to create a docker-network `global-nginx-proxy-net` which is used to connect both docker-compose setups.
Additionally, a grafana.env file has to be created. All of this is being done using ansible and therefore not present in this repository.

