# Overview

Just a small sample project for a **Nodejs REST API** with some **logging** ([Resource](https://www.section.io/engineering-education/how-to-create-a-simple-rest-api-using-typescript-and-nodejs/)).

## Packages:

- **TypeScript**: A TypeScript compiler with static set type definitions.
- **Ts-node**: Allows us to run and configure Typescript execution environments.
- **Express**: Node.js web application framework for setting and managing web-based server.
  - @types/express: Type definitions for Express.
- **Morgan**: A Node.js HTTP request logger middleware for Node.js.
  - @types/morgan
- **Axios**: A Node.js promise-based HTTP client library for Node.js, for sending HTTP requests to query and consume resources from APIs.
  - @types/Axios
- **Nodemon**: A server utility library for monitoring changes of the code on a text editor. It automatically restarts the server whenever code changes are detected.




------------------------------------------------------------------------------------------------
# Setup

All steps setting up the project as follows:

- `mkdir <project_name>`
- `cd <project_name>` and `npm init -y` to create package.json
- `npm install typescript ts-node express @types/express morgan @types/morgan axios @types/axios nodemon`
- `tsc --init` to generate tsconfig file
  - To execute Typescript with Node.js, we need a tsconfig.json file which sets all the environments required to run Typescript.
- `git init` and `echo 'node_modules/' > .gitignore`





------------------------------------------------------------------------------------------------

# Todo

- swagger integration ?
- (unit) testing ?
