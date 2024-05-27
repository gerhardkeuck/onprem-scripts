Script taken from `https://raw.githubusercontent.com/longhorn/longhorn/v1.4.3/scripts/environment_check.sh` from https://longhorn.io/docs/1.5.0/deploy/install/#using-the-environment-check-script

Adjusted base image location to use explicit registry path.

## How to use

1. Make sure the `docker.io/library/alpine:3.12` container image has been stored in nexus.

2. Execute the script:

Execute with:
```shell
curl -sSfL https://raw.githubusercontent.com/mmswire/onpremise-scripts/main/longhorn/v1.4.3/environment_check.sh | bash
```
