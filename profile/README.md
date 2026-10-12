# Outspark

Cada idea tiene un recorrido. Proyecto universitario de Complejidad Algorítmica, UPC, 2026-20.

| Repositorio | Contenido |
| --- | --- |
| [outspark-report](https://github.com/outspark-app/outspark-report) | Informe, plan, modelo de datos y diseño |
| [outspark-backend](https://github.com/outspark-app/outspark-backend) | API local, handler Lambda, DynamoDB y algoritmos del aplicativo |
| [outspark-landing](https://github.com/outspark-app/outspark-landing) | Presentación del producto |
| [outspark-app](https://github.com/outspark-app/outspark-app) | Boceto navegable del aplicativo |
| [outspark-facebook-grafo](https://github.com/outspark-app/outspark-facebook-grafo) | Cuaderno reproducible y análisis histórico de Facebook |

Los repositorios de desarrollo son privados y requieren acceso a la organización. El grafo histórico es público.

Arquitectura prevista: Lambda Python, DynamoDB, API Gateway y Cognito; archivos estáticos en S3/CloudFront. Backend local persistente y páginas React/Vite disponibles. Integración del aplicativo, Flutter web y despliegue AWS pendientes.

Para el equipo: empieza por el README de **outspark-report** para las decisiones, el de **outspark-backend** para la API y el de cada página para ejecutarla. El material del profesor se mantiene separado del código.
