# ITB FHIR Test Services

This project provides a sandbox environment for testing FHIR server and client application through the Interoperability
Test Bed (ITB).

More information on the `fhir-itb-services`, can be found in
the [fhir-itb-services/README.md](fhir-itb-services/README.md) file.

Information on ITB can be found at https://www.itb.ec.europa.eu/.

## Development

During **development**, one should run the sandbox using the root `docker-compose.yml`.

E.g.:

```shell
docker compose up 
```

To include the `fhir-test-services` image, add the `full` profile:

```shell
docker compose --profile full up 
```

The `fhir-test-services` image is built from
[dist/itb-fhir-test-services/Dockerfile](dist/itb-fhir-test-services/Dockerfile).
