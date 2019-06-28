# Prometheus-Grafana-setup

This includes a docker-compose file which creates containers of Prometheus and its components like nodemanager,cadvisor etc. The data can be visualized using grafana which will also be created in a separate container using the docker-compose file. Here I have used a sample wordpress site running a database to test the setup by applying load on the site and monitoring the CPU usage of the site with Prometheus and visualizing the data through Grafana.
