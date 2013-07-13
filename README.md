NOCMATE-Rx
==========

Project NOCMATE-Rx

The system helps to view operations data,detect and respond to the changes and is used in day to day decision making to identify opportunities to drive operational efficiencies—as they happen.

Expanding the acronym NOCMATE-Rx :

* N -> Network / Notifications
* O -> Operations / (Operational Excellence)
* C -> Center / (Central Monitoring Tool) / Correlation / Custom Metrics
* M -> Metrics / Monitoring
* A -> Alerts / Analysis
* T -> Trends via Dashboards / troubleshooting / Thresholds
* E -> Events

* R -> Real-time / Reporting / Resource / Release Tracking
* x -> Everything/Anything


Systems:

* Security Devices(IDS/IPS,WAF)
* Loadbalancer(F5:GTM/LTM)
* NetworkDevices (Firewalls,Switches,Routers)
* WebServers(Apache,ngnix)
* ApplicationServers(Tomcat,JBoss,JETTY)
* SOA
* Caching(Memcache,Redis,Ehcache)
* Data Stores(MySQL,Cassandra,MSSQL)
* Logfiles
* Virtualization(XEN Servers)
* Web-Analytics(Omniture)

Solutions:

* Identification of sources, defining frameworks for collection mechanisms.
* Writing/extending/customizing already available open source tools (like Graphite,ElasticSearch,Nagios/Centreon,Cheetah, F5)
* Integrating components like trending, alerting, reporting yet keeping them separate.
* Collecting metrics across so many horizontals and verticals can be very challenging this is where Visualization via dashboards form one the most crucial components because not only do they act as the presenting layer for the various metrics being collected , but also gives each set of user the power to see what metrics are of their interest.

Tools :

In-House Developed:

* Inventory Management -> Puppet / Facters / Django(Python) based fact DB.
* Poller Framework -> DBPoller etc to poll any SQL query from any RDBMS and create Key-Values to make them as metrics. Uses celery for distributed task processing.
* Custom Dashboards -> Django(Python)
* Cheetah -> Python, Selenium-RC and Jenkins(Hudson) integration for Real Time monitoring of website with nice Reporting and Alerting system developed from scratch.
* LBManager -> Manage and Monitor the Load Balancer

Open Source:

* Graphite -> Real-time Graphing / Trends
* Diamond -> python daemon for System metrics
* Nagios/Centreon -> system monitoring and Centralized Alerting framework
* Observium -> Network Monitoring
* JMXSH -> Java Apps Monitoring
* Logster -> Parse web/application log files, generate metrics for Graphite
* Puppet -> Infrastructure-As-Code
* RabbitMQ (Messaging system) -> Monitoring metrics
* Logstash -> Centralized log collection , Indexing using ElasticSearch as backend and Kibana as Web interface
