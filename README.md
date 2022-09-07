# Observatorium Operator

[![Build Status](https://circleci.com/gh/observatorium/operator.svg?style=svg)](https://circleci.com/gh/observatorium/operator)

Operator deploying the Observatorium project.
Currently, this includes:

1. the operator itself; and
1. example configuration for deploying Observatorium via the Observatorium Operator.

For more information on the operator, see the [Observatorium Operator documentation](./docs/deploy-operator.md).

## Development

We provide a few make commands that should help you getting started with development a bit quicker.

There is `make generate` that will generate new Kubernetes client files after updating the types for the Custom Resource Definition.

Then there is `make manifests` which is going to generate all manifest YAML files from jsonnet so that things are kept up-to-date.

If you need to update the dependencies for jsonnet simply use `make jsonnet-update` or more specifically `make jsonnet-update-deployments`.

Rebuild Image: Thu Jun 16 10:19:08 EDT 2022


Rebuild: Wed Sep  7 12:39:40 EDT 2022
