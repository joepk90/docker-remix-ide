# Docker Remix IDE
Remix IDE setup using Docker. Useful for following Solidity Tutorials and tracking the code via git.

The intention of this project was to replicate Remix's IDE Locally:
[https://remix.ethereum.org](https://remix.ethereum.org)

This project runs remixd via node, and the remix ide via docker. It could be worth getting remixd working in docker-compose as well. There is an open branch looking into this [setup-remixd-in-docker](https://github.com/joepk90/docker-remix-ide/compare/main...setup-remixd-in-docker).

## Project Setup

*Install NPM Dependancies*
```
npm install
```

*Run Remixd*
```
make remixd
```

*Run Docker Compose*
```
make compose-up
```

## Using Remix IDE

Go [http://localhost:8080](http://localhost:8080) to view Remix IDE in the browser.

From here, either use the IDE to test contracts, or Connect to Localhost to use your local file system - the contracts and scripts stored in this project.

In order for Localhost to work, `remixd` must be running.


## Reference Links:
- https://github.com/remix-project-org/remix-project/blob/master/docker-compose.yaml