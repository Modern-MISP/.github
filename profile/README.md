## Hi there 👋

Modern MISP, a re-implementation of [MISP](https://github.com/MISP/MISP).

### History

In 2023 [KIT-CERT](https://cert.kit.edu) tried joining the MISP-Users Community. Unfortunately, MISP cannot be used with anything besides MySQL.
Setting up a new database next to our existing postgres cluster was not our dream solution.
So, with the help of computer science students at KIT, we designed a new MISP, with separation between backend and frontend and a separation between
api calls and long-running background tasks.
Modern MISP was born.

### Goal

We want to provide a drop-in replacement. You should be able to keep your database, your scripts using the API, but benefit from a correct OpenAPI Specification.

### Current status

We are currently in an early development stage. If you want to see our progress, see how to [deploy your own Modern MISP](https://github.com/Modern-MISP/deployment).
Not all features of MISP are or will be implemented.
