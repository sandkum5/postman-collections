# postman-collections
Postman Collections Backup

### hx-api.postman_collection.json
#### Collection of HX API calls. 

##### Create following Environment variables with values: 
    - hx_ip
    - hx_user
    - hx_passwd

##### Create below Environment variables with empty values: 
    - access_token
    - refresh_token
    - token_type
    - hx_cluster_name
    - hx_cluster_uuid
    - node_uuid

##### "Obtain Access Token" request will fill the "access_token", "refresh_token" and "token_type" variable values. 
##### "Get HX Cluster Info" request will fill the "hx_cluster_name" and "hx_cluster_uuid" variable values. 
##### "node_uuid" variable needs to manually specified for "entermaintenancemode" and "exitmaintenancemode" requests. 


### cimc.postman_collection.json
#### Collection of Cisco IMC API calls. 

##### Create following Environment variables with values: 
    - imc_ip
    - imc_user
    - imc_passwd

##### Create below Environment variables with empty values: 
    - XAuthToken


### ucs-central.postman_collection.json
#### Collection of Cisco UCS Central XML API calls. 

##### Create following Environment variables with values: 
    - central_ip
    - central_user
    - central_passwd


### intersight-oauth2.postman_collection.json
#### Collection of Cisco Intersight API calls using OAuth2 Token.

##### Create following Environment variables with values: 
    - oauth_user
    - oauth_passwd