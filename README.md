# Medical microservices configuration

This coursework contains:

- `config-service`: Spring Cloud Config Server, running on port `8888`.
- `medical-config-repo`: Git repository containing centralized service configuration.

Start the Config Service:

```bash
cd config-service
mvn spring-boot:run
```

Then open `http://localhost:8888/patient-service/default`.
# micro_btvn07_01
