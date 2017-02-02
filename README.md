# Linux Server Configuration #

This is the README for the Linux Server Configuration project.

## IP Address and SSH port ##

IP: http://35.166.206.142/

SSH Port: 2200

## Public URL ##

http://ec2-35-166-206-142.us-west-2.compute.amazonaws.com/

## Configuration ##

* Created a user as required by project outline
* Disallowed remote root access
* Created another superuser for use to set up project
* Configured firewall to allow only required ports
* Disabled password authentication
* Updated packages
* Changed SSH port from default
* Installed and configured apache2
* Installed and configured postgresql
* Installed wsgi and configured Apache accordingly
* Installed Flask
* Installed SQLAlchemy


### Added packages (Ubuntu package names)###

* apache2
* postgresql
* python-flask
* python-flask-sqlalchemy
* python-psycopg2
* python-httplib2
* python-oauth2client
* git
* tree

### Sites consulted for advice ###

* http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
* http://killtheyak.com/use-postgresql-with-django-flask/
* https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps
* https://www.digitalocean.com/community/tutorials/how-to-secure-postgresql-on-an-ubuntu-vps
* https://support.rackspace.com/how-to/postgresql-creating-and-dropping-roles/
* https://wiki.apache.org/httpd/CommonMisconfigurations
* http://packages.ubuntu.com/search?keywords=tree&searchon=names&suite=yakkety&section=all
