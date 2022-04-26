# Route Finder (Frontend)

## Description

The aim of this project is to create a web-based service which allows for a quicker and more
efficient way to traverse a library or similar environment. Specifically, this app will be a
list of items, with the feature of giving you both:

-   The most efficient (based on distance to walk) order in which to pick up these items
-   A visual map of the pathway to follow

This idea builds on existing services from department stores, adding what we believe to be a
key feature of navigation around the building.

This repository contains the frontend code of the project, which is constructed as a React client
application for the backend, found [here](https://github.com/isaac-list/store_project/).

## Getting Started

### Installing Nodejs and NPM

To set up your environment, install Node and NPM using docs/setup/nvm-setup.sh

### Installing Dependencies

Once Node and NPM are installed (at least Node version 14LTS), run
`npm install`
in the root of the "client" directory.

### Building for Deployment

To build the React client, execute the script `build.sh` from the root directory,
or run `npm run build` from /client

The frontend is currently being deployed on Netlify at
[route-finder.netlify.app](https://route-finder.netlify.app).

## License

This project is licensed under the second version of the Mozilla Public License, the terms of
which may be found [here](https://www.mozilla.org/en-US/MPL/2.0/).
