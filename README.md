# ansible-playbook-server
An ansible playbook for setting up servers.

## Roadmap
- System Installs
  - ansible
  - git
  - nginx
  - certbot
  - podman

- Services
  - keycloak [{idp|iam}.company.com]
  - Gitlab [{git|cvs}.company.com]
  - Mattermost [{mm|chat}.company.com]
  - Nextcloud [cloud.company.com]
  - Uptime Kuma [uptime.company.com]
  - Maptiler,Geoserver,Martin [maps.company.com]
  - Airflow,Argo [flows.company.com]
  - WikiJS,Bookstack [{docs|wiki}.company.com]

- Databases / Event Streaming
  - postgres (timescaledb, postgis)
  - mongodb
  - kafka - confluent platform
  - graph (?)
  - redis | memcached

- SysMon [hostname.company.com/]
  - portainer [/portainer]
  - rancher [/rancher]
  - prometheus
  - grafana [/dashboard]
  - cAdvisor
  - node-exporter
  - adminer [/debug/adminer]
  - mongo-express [/debug/mongo-express]
  - kafdrop [/debug/kafdrop]
  - rebrow [/debug/rebrow]
