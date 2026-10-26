# Medical microservices configuration

This coursework contains:

- `config-service`: Spring Cloud Config Server, running on port `8888`.
- `patient-service`: Spring Boot service that loads its configuration from Config Server.
- `medical-config-repo`: Git repository containing centralized service configuration.

Start the Config Service:

```bash
cd config-service
mvn spring-boot:run
```

Then open `http://localhost:8888/patient-service/default`.

Start the Patient Service in a second terminal:

```bash
cd patient-service
mvn spring-boot:run
```
# micro_btvn07_01
