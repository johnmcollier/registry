# registry
Devfiles registry - storing contents of the common devfile registry that feeds into the OCI based common registry

## Build

To build the contents of this registry, run `docker build -t registry-artifacts .`

## Deploy

Specify the `devfile-registry-artifacts` image when deploying the OCI registry on a cluster to deploy the registry with your own devfiles.