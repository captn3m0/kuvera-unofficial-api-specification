# Kuvera Unofficial API Specification

Please see https://captnemo.stoplight.io/docs/kuvera/

## Terms of Service

I'm not responsible. Use at your own risk. This is a read only API, so you can't use this to manage your funds.

## Clients

Generate the Python client by running:

    docker run --rm -v "$PWD":/local openapitools/openapi-generator-cli generate -c /local/openapi-generator-config.yml  -i /local/reference/Kuvera.yaml -o /local/src/python -g python

The generated client is currently broken due to bugs in openapi-generator which misses a few imports.