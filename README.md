# Shared-Backpack-docs

## Components

The Document Section for the Shared-Backpack Project.

The Project is particulary divided into major 4 part 

1. Shared Backpack user app
2. Shared Backpack mini admin app
3. Shared Backpack admin panel
4. Shared Backpack API

## Comunity Impact

The project focuses on 

1. Cheap Travel
2. Level Group Travel

## Tech Stack

1. Flutter (user app)
2. Flutter (mini admin)
3. Vue.js (admin panel)
4. Nodejs and MongoDB (API)

## Installation

The contents of the `Shared-Backpack-docs` repo is used to automatically create [the Shared Backpack documentation website](https://the-shared-backpack.github.io/Shared-Backpack-docs/). The automation uses [Docusaurus](https://docusaurus.io/docs/), a modern static website generator.

Intallation will vary depending on whether you use the `yarn` or `npm` packages. Visit the [Docusaurus installation web page](https://docusaurus.io/docs/installation) if you have any difficulties with the steps below.

## Prerequisites

- Nodejs
- Git 

## Using Yarn

The steps are simple:

1. Clone this repository
2. Install `yarn` on your system

```console
$ git clone https://github.com/The-Shared-Backpack/Shared-Backpack-docs
$ cd Shared-Backpack-docs
$ sudo apt-get -y install yarn
$ yarn add docusaurus
```

## Using NPM

```console
$ git clone https://github.com/The-Shared-Backpack/Shared-Backpack-docs
$ cd Shared-Backpack-docs
$ npm install
```

# Running the Development Server

To preview your changes as you edit the files, you can run a local development server that will serve your website and it will reflect the latest changes.

## Using Yarn

Follow these steps:

```console
$ cd Shared-Backpack-docs
$ yarn run start
```

By default, a browser window will open at http://localhost:3000.

This command starts a local development server and open up a browser window. Most changes are reflected live without having to restart the server.

## Using NPM

```console 
$ npm start
```

# Building Static HTML Pages

**In most cases is unnecessary**. Running the `development server` will be sufficient.

If you need to generate static HTML pages (unlikely), then follow these steps.

```console
$ yarn run build
```

This command generates static content into the `/build` directory and can be served using any static contents hosting service.

 
