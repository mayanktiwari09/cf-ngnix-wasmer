# Run Nginx with Wasmer on Cloud Foundry

This example runs Nginx with [Wasmer](https://wasmer.io/) on Cloud Foundry.

## Running

Clone the repositiry and run cf push with custom buildpack as follows:

```
cf push wasm-ngnix -b https://github.com/mayanktiwari09/cf-buildpack-wasmer.git
```
