# DAMEN (Docker, Alpine, Mongo, Express, Node - SERVER)

Template for initial docker project setup using node:alpine, mongo-db, mongo-express, express-js and webpack. Features transpilation via babel, seperate client / server bundles, hot module re-loading and a reverse-proxy via nginx. Jest included for testing.

Designed not to conflict (even with it's self) fire up 10 versions of the same code just change the instance_id and/or app_name.

Provide a minimal-fuss go-to application stack that can be re-used and up-dated over time. Doesn't have a preference to front-end tech, use React, Vue, Angular whatever you like.

## To use
- create your .env file (from .env.example)
- run ./deploy.sh
- update your windows hosts file to point whatever-is-in-your-nginx.conf to 127.0.0.1
- enjoy