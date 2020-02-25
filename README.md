# express-boilerplate

A bare-bones REST API using Express, which uses Winston for logging

## Install

`yarn`

## Startup

`yarn start`

You can test via `curl`

`curl --include --no-buffer http://localhost:2000/`

## Logging

### Logging directory

The logging directory is specified using the `LOGGING_DIRECTORY` variable in the config file.

## Configuration

Uses separate config files in `/config` for each environment i.e `development`,`test`, and `production`
