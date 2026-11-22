# CST8915 – Lab 8: Algonquin Pet Store (On Steroids)

## Demo Video
[https://youtu.be/oIaUkmGNtII](https://youtu.be/oIaUkmGNtII)

## Docker images:

| Service | Docker Images |
|---|---|
| Store Front | [bou0167/store-front:lab8](https://hub.docker.com/r/bou0167/store-front?tag=lab8) |
| Store Admin | [bou0167/store-admin:lab8](https://hub.docker.com/r/bou0167/store-admin?tag=lab8) |
| Order Service | [bou0167/order-service:lab8](https://hub.docker.com/r/bou0167/order-service?tag=lab8) |
| Product Service | [bou0167/product-service:lab8](https://hub.docker.com/r/bou0167/product-service?tag=lab8) |
| Makeline Service | [bou0167/makeline-service:lab8](https://hub.docker.com/r/bou0167/makeline-service?tag=lab8) |
| AI Service | [bou0167/ai-service:lab8](https://hub.docker.com/r/bou0167/ai-service?tag=lab8) |
| Virtual Customer | [bou0167/virtual-customer:lab8](https://hub.docker.com/r/bou0167/virtual-customer?tag=lab8) |
| Virtual Worker | [bou0167/virtual-worker:lab8](https://hub.docker.com/r/bou0167/virtual-worker?tag=lab8) |

## Managed Azure Service Alternatives
### Azure DocumentDB (MongoDB Alternative)
Azure DocumentDB is a managed document database with MongoDB compatibility. It can replace a self-hosted MongoDB database, reducing database maintenance and infrastructure management.

### Azure Service Bus (RabbitMQ Alternative)
Azure Service Bus is a managed messaging service that supports queues and topics. It can replace self-hosted RabbitMQ for communication between microservices, reducing broker maintenance.

However, migration may require application changes because Azure Service Bus and RabbitMQ use different messaging protocols and features.