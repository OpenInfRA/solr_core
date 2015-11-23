# solr_core
This repository contains the OpenInfRA core definition for the Solr Server.

## Installation
The OpenInfRA Solr core must be placed in the path that was specified in the [OpenInfRA properties file](https://github.com/OpenInfRA/core/blob/master/openinfra_core/src/main/resources/de/btu/openinfra/backend/properties/OpenInfRA.properties) as file path. There you must create a folder with the name _solr_ where all the files from this repository must be placed at.

Be careful when editing the [schema.xml](openinfra/conf/schema.xml). Changes can influence the index and search process of OpenInfRA.

For further configuration of the Solr core see the official [Solr documentation](https://cwiki.apache.org/confluence/display/solr/Apache+Solr+Reference+Guide).
