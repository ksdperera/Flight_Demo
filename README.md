# Flight_Demo

cp master-datasources.xml {$CEP_PRODCUT_HOME}/repository/conf/datasources/

cp eventpublishers/. {$CEP_PRODCUT_HOME}/repository/deployment/server/eventpublishers/

cp eventstreams/. {$CEP_PRODCUT_HOME}/repository/deployment/server/eventstreams/

cp executionplans/. {$CEP_PRODCUT_HOME}/repository/deployment/server/executionplans/

cp lib/. {$CEP_PRODCUT_HOME}/repository/components/lib/

execute db/Southwest_Airlines_DB.sql

simulator import sample_dataset/.

