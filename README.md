### Description

This is a sample monorepository to illustrate the mechanics of the VSM GitHub integration. Please find the extensive user documentation [here](https://docs-vsm.leanix.net/docs/github-repository#support-for-mono-repos).

## Structure of this repository

```
services
    ├── payment-service
    │   ├── lx-manifest.yaml
    │   └── src
    └── pricing-service
        ├── lx-manifest.yaml
        └── src
        
```
where `payment-service` and `pricing-service` represent actually deployed services.