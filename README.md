# config-repo

Depot Git qui contient les fichiers de configuration des microservices.
Il est lu par le **Config Server** (Spring Cloud Config).

| Fichier | Utilise par |
|---|---|
| `application.properties` | tous les services |
| `product-service.properties` | product-service (defaut) |
| `product-service-dev.properties` | product-service (profil dev) |
| `product-service-prod.properties` | product-service (profil prod) |
| `order-service.properties` | order-service (defaut) |
| `order-service-dev.properties` | order-service (profil dev) |
| `order-service-prod.properties` | order-service (profil prod) |

Regle de nommage : `{spring.application.name}-{profil}.properties`.
