# grpc-oauth2-keycloak-docker
Simple example project to run [gRPC](https://grpc.io/) behind OAuth2 using [keycloak](https://www.keycloak.org/) in docker container using [Svelte](https://svelte.dev/) with [Material UI](https://sveltematerialui.com/)

## Build and start
1. add `127.0.0.1   keycloak.localtest.me oauth2-proxy.localtest.me` to your hosts file
1. run `docker-compose up`
1. keycloak might need very long to start (~3 minutes), be patient!
1. visit [http://localhost:4000](http://localhost:4000) in your browser.

## Contributions
Based on https://github.com/oauth2-proxy/
