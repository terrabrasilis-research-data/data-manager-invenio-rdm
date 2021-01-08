# TerraBrasilis Research Data - Data Manager Invenio RDM

The Data Manager is responsible for the support portion of the platform. In the context of infrastructure, this includes the creation, management and delivery of Research Data Repositories. It uses Invenio Research Data Managemen.

Invenio RDM Installation
------------

1. `cd ...`
2. `cd ..r`
3. run the following command: `docker-compose up -d --build` # it will run all the needed containers
4. run the following command: `docker exec -it terrabrasilisrd_ckan /usr/local/bin/ckan-paster --plugin=ckan sysadmin -c /etc/ckan/production.ini add ckanadmin`

Then you can open the Invenio RDM at [http://localhost:5000.](http://localhost:5000.).

See the `Invenio RDM Documentation <https://invenio-app-rdm.readthedocs.io/`_ for installation instructions.

