# Custom Repository for RancherOS

Custom repository for RancherOS providing service and console definitions

## Services

|Name              |Description                                                 |Image                                                            |
|------------------|------------------------------------------------------------|-----------------------------------------------------------------|
|`dns`             |provides a DNS service based on bind                        |[capybara1/dns](https://hub.docker.com/r/capybara1/dns)          |
|`docker-gc`       |provides the docker-gc from Spotify                         |[spotify/docker-gc](https://hub.docker.com/r/spotify/docker-gc)  |
|`firewall`        |provides a service that restores iptable rules during bootup|[capybara1/firewall](https://hub.docker.com/r/capybara1/firewall)|
|`system-docker-gc`|same as `docker-gc` but controls `system-docker` instead    |[spotify/docker-gc](https://hub.docker.com/r/spotify/docker-gc)  |

## Consoles

|Name     |Description                            |Image                                                                          |
|---------|---------------------------------------|-------------------------------------------------------------------------------|
|`ansible`|a console designed to work with Ansible|[capybara1/ansible-console](https://hub.docker.com/r/capybara1/ansible-console)|
