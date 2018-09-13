# warmdown
Is the server is a physical  host or vm or container? what is the list of application's url (user services, management, monitoring, etc.) which login credentials will be used to connect to each url  what is the quick win network infrastructure and architecture of the application.  where the installation and management documentation of application  where is the exploitation documentation etc. To solve all theses problems  I have decided to create a Human Manageable Application Execution Context. 

# Design philosophy: KISSN (KISS for novice) HATEOAS Linked Data SKOS.
City in Country
DC in City
Zone in DC
Rack in DC Zone
Cluster in Rack
Container, VM, Host of virtualization, Baremetal in Cluster
Application run in Container
Application run in VM
Application run in Bare Metal
Application run in AppServer (Apache IIS nodejs Glassfish c-server, django, nginx, undertow, wildfire, etc.)

## First View is Host view :  List of Services Application Installed 
* Host Os name version kernel distrib, architecture
* Application software version
*  Installation Main Folders
*  Main Configuration Files
*  Services/Daemons to run for application (Commands that Users have to use to run theses services and daemons)
*  List of Url/Uri  with type of port, port number 
*  User Credentials per Url/Uri
*  dns name used per URL/URI  per services
*  Services and daemon description 
*  Quick broad architecture of application (services, daemon, module) 
*  Management documentation 
*  Installation documentation
*  Update and Upgrade documentation
*  Supervision documentation
*  External dependencies (network, infra, application, services, credential, ws, db, amqp, cloud etc.)
