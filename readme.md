# Docker Remix IDE
Remix IDE setup using Docker. Useful for following Solidity Tutorials and tracking the code via git.


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
