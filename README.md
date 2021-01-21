# postman-collections
Postman Collections Backup

### HX-API.postman_collection.json
#### Collection of HX API calls. 

#### Create following variables with values: 
    - hx_ip
    - hx_user
    - hx_passwd

#### Create below Variables with empty values: 
    - access_token
    - refresh_token
    - token_type
    - hx_cluster_name
    - hx_cluster_uuid
    - node_uuid

#### "Obtain Access Token" request will fill the "access_token", "refresh_token" and "token_type" variable values. 
#### "Get HX Cluster Info" request will fill the "hx_cluster_name" and "hx_cluster_uuid" variable values. 
#### "node_uuid" variable needs to manually specified for "entermaintenancemode" and "exitmaintenancemode" requests. 

