# Dist build assets

This folder holds Dockerfiles used when building project images.

## fhir-test-services

Used by the root `docker-compose.yml` (`--profile full`) to build the
`fhir-test-services` container from local sources.

See [itb-fhir-test-services/README.md](itb-fhir-test-services/README.md).

## gitb-ui-fhir-sandbox

Optional Dockerfile to package `gitb-ui` with the FHIR community configuration
from `config/data`.

See [gitb-ui-fhir-sandbox/README.md](gitb-ui-fhir-sandbox/README.md).

To run the sandbox locally, use the root Compose file:

```shell
docker compose --profile full up
```
