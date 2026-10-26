# Config Service

Spring Cloud Config Server for the medical microservices coursework.

## Run

```bash
cd config-service
mvn spring-boot:run
```

The server reads configuration from the local Git repository
`../medical-config-repo` and exposes it at:

```text
http://localhost:8888/patient-service/default
```

To use another repository, set `CONFIG_REPO_URI`, for example:

```bash
CONFIG_REPO_URI=file:///Users/your-name/medical-config-repo mvn spring-boot:run
```
