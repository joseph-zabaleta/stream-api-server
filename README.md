# Stream Project API Server

## Table of Contents

---

-   [Overview](#overview)
-   [Installation](#installation)
-   [Authors](#authors)
-   [Collaborations](#collaborations)
-   [License](#license)
-   [Acknowledgements / Resources](#acknowledgements-/-resources)

---

## Overview

This is a simple json-server application. Used to create a simple API for a React Front End project. The main project repo is here [Stream Project](https://github.com/joseph-zabaleta/streams-client)

## Installation

API server makes use of the npm package `json-server` follow the code block below to get started.

```bash
git clone https://github.com/joseph-zabaleta/stream-api-server
cd stream-api-server
npm install
```

After installation of the dependencies, there is one more final piece of configuration before we can start, that is to create a `db.json` file to act as our database. With in the root run the following command

```bash
touch db.json
```

Now you are ready to start up this local API server

```bash
npm start
```

## Authors

-   Software Developer: Joseph Zabaleta
    -   [Official Github](https://github.com/joseph-zabaleta)

## License

This project is under the MIT License.

## Acknowledgements / Resources

-   [json-server Documentation](https://www.npmjs.com/package/json-server)
-   [Modern React with Redux](https://www.udemy.com/course/react-redux/)
