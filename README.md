### openssl genrsa -out server.key

### openssl req -new -key server.key -out server.csr


### openssl x509 -req -in server.csr -signkey server.key -days 365 -out server.crt


### docker compose build

### docker compose up mysql_keycloak

### docker compose up keycloak_w


## source
## https://github.com/KavinduGayan/keycloak-docker-compose


.env
KEYCLOAK_ADMIN=grzegorz
KEYCLOAK_ADMIN_PASSWORD=password
MYSQL_ROOT_PASSWORD=password
KC_HOSTNAME=some-hostname
KC_HOSTNAME_URL=https://some-hostname
