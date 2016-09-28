
This is a containerized stack for Appleseed Search Platform ( part of the Appleseed Framework ). 

Search Platform Internal Components :

- TODO: Appleseed.Search.Web.User.Ng.Solr (will be pulled from release)
- TODO: Appleseed.Search.Web.User.Ng.Elastic (will be pulled from release)
- TODO: Appleseed.Search.Web.Admin  (will be pulled from release)
- TODO: Appleseed.Search.Index.Solr (solr + appleseed-public)
- TODO: Appleseed.Search.Index.Elastic (elastic + appleseed_public)
- TODO: Appleseed.Search.Storage (busybox) 
- TODO: Appleseed.Search.Engine (mono + Search.Console) 

Other than the components which are part of the Search stack, this stack leverages out of the box containers that are widely available. 

Search Platform External Components :

- TODO: Nginx or Apache HTTPd (to serve Single page apps )
- TODO: MySQL, MariaDB or PerconaDB (disabled, for internal needs, tests)
- TODO: PostgreSQL (disabled, for internal needs, tests)
- TODO: Solr (disabled, for solr index endpoint)
- TODO: Elasticsearch (disabled, for elastic index endpoint)
- TODO: Redis (disabled, for internal needs, tests)
- TODO: Memcached (disabled, for internal needs, tests)
- TODO: RabbitMQ (disabled, for internal needs)
- TODO: MongoDB (disabled, for internal needs)
- TODO: busybox (disabled, for storage of configuration)
- TODO: mono (disabled, for running .net pre core code)
- TODO: aspnet (disabled, for running .net core code )
- TODO: jdk (disabled, for running java/scala code)

This stack's design was informed by [Docker best practices](https://docs.docker.com/articles/dockerfile_best-practices/) and by other 
projects such as [php-boilerplate-docker](https://github.com/webdevops/php-docker-boilerplate/) , [ckan-docker](https://github.com/ckan/ckan-docker/) ,
[dotnet-nginx-kestrel](https://github.com/sesispla/docker-nginx-kestrel) 
Though it uses third party dockers, each dependent docker can be configured `docker/` directory. Developers / administrators
should not have to do much or any configuration in code. 

