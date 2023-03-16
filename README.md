![xkite GUI](https://raw.githubusercontent.com/oslabs-beta/xkite/main/images/banner_800x450.png)

# create-xkite-cli <br> ![version](https://img.shields.io/badge/version-1.0.1-blue.svg) ![license](https://img.shields.io/badge/license-MIT-blue.svg) <span> <a href="https://xkite.io/"> <img src="https://img.shields.io/twitter/url/http/shields.io.svg?style=social" /> </a></span>

Creates the xkite Command Line Interface (CLI) Utility.

Command Line Interface for xkite, a Kafka Integrated Testing Environment. Another tool in the xkite library to give the user flexibility and control over their Kafka ecosystem.

- Easy to use Command Line Interface (CLI) to interact with the xkite-core library. It’s a simple alternative to the full xkite GUI, meant to provide users with the ability to automate their testing using scripts.
- Configure a custom docker ecosystem using command line inputs or a <code>config.json</code> file, deploy, pause/ unpause, shutdown, and remove containers and volumes.
- Download the docker ecosystem configuration (package.zip) containing the docker-compose.yml file and dependencies in order to deploy their ecosystem on a cloud instance/remote server by simply running docker-compose up.
- Acts as a remote client to interface with the xkite GUI server. The user can perform all the aforementioned functions provided remotely on the xkite GUI server by providing the URL as a configuration input.
- More granular control over which docker images they choose to deploy (something that is not configurable currently with the xkite GUI).

# Dependencies

- Latest stable versions of Node.js and NPM installed
- Latest stable version of <a href="https://docs.docker.com/compose/install/">docker-compose</a> installed.
- Clone repository: <code>git clone https://github.com/oslabs-beta/xkite-cli.git</code>
- Install dependencies: Run <code>npm install</code> inside the project folder

# Quickstart

To install the <code>xkite-cli</code> into your environment just simply run the following command:

```sh
  $ npx create-xkite-cli <directory-name>
```

After the installation is complete, you will be able to run <code>xkite-cli</code> as follows:

```sh
  $ xkite-cli
```

![npx create-xkite](./create_xkite_cli.gif)

## [See the xkite-cli documentation for further details](https://github.com/oslabs-beta/xkite-cli '@embed')
