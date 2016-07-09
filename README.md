# particles-api-gateway

Particles for [condensation](https://github.com/SungardAS/condensation) that help build an AWS API Gateway.

## Use

    > npm install
    > gulp condensation:build
    > gulp condensation:deploy

Templates will be created in the `dist` directory

To build CloudFormation templates, fill 'region' and 'bucket' in `config/default.js` with bucket configuration

## Particles

A stack that will build an API Gateway.
