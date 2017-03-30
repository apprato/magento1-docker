## Magento 1 Dockerized Environment Base Setup (OSX)

# Containers

* nGinx
* PHP / PHP 5.6
* MariaDB
* Redis


# Install Magento via composer or Git
http://devdocs.magento.com/guides/v2.0/install-gde/prereq/integrator_install.html


# Add local URL to hostfile
Use IP for local host, e.g.

/etc/hosts
192.168.99.100 magento.dev

# Create dockerised environments
docker-compose up -d
docker-compose build