# keycloak docker compose

This is project is used to demonstrate how to configure [Keycloak](http://www.keycloak.org/index.html), which is developed by [Redhat](https://www.redhat.com/en), as an IDP for federated login to AWS.

# usage

```
docker-compose up -d
```

Open your browser and navigate to http://0.0.0.0:18080.

**Note:** I went to the trouble of generating some random default passwords but you should still set your own in the `docker-compose.yml`.