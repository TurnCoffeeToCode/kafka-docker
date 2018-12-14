kafka-docker
============

This repository is a fork of [wurstmeister/kafka-docker](https://github.com/wurstmeister/kafka-docker) with some specfific changes to run our Pegasus Kafka environment.

## How to run

Type the following command in your terminal to run it with a single broker.

`docker-compose -f docker-compose-single-broker.yml up`

With this it will run with `KAFKA_ADVERTISED_HOST_NAME` as `127.0.0.1`.

The file is configured that it will create the following topics

- `pfc-power-import`

The full documentation you can find [here](https://github.com/wurstmeister/kafka-docker).