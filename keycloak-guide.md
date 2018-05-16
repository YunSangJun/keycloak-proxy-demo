# keycloak guide

## Create and configure realm

1. Create realm
![Create realm](./img/add_realm.png)

2. Configure realm general
![Create realm](./img/realm_general.png)

3. Configure realm login
![Create realm](./img/realm_login.png)

4. Confirm realm public key
<br>Click "Public key" button and confirm the key on pop-up window.
![Create realm](./img/realm_publickey.png)

## Create Client

1. Click "Create" button
![Create Client](./img/add_client1.png)

2. Insert "Client ID" and Save
![Create Client](./img/add_client2.png)

3. Configure client settings
<br>Note: Valid Redirect URIs is a list of URLs to accept as Redirect URLs. 
In this article, we will use `http://WORK_NODE_IP:NODE_PORT` as Redirect URL. 
![Create Client](./img/client_settings.png)

4. Confirm client secret
![Create Client](./img/client_secret.png)

## Create Role

1. Click "Add Role" button
![Create Role](./img/add_role1.png)

2. Insert "admin" and Save
![Create Role](./img/add_role2.png)

