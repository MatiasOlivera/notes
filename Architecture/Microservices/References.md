# Microservices

## Microservices vs monolith

**Microservices**

- Every app function is its own service (separation of concerns)
- Own container
- Communicate via APIs

Advantage

- language
- Iterate at will/devops pipeline
- Less risk in change
- Independent scaling

Questions:

- Are there APIs being used by multiple services?
- Is decoupled?
- Is there a separation of concerns based on business requirements?

**Monolith**

- Server-side system based on a single application
- Easy to develop, deploy, and manage

Challenge

- Highly dependent
- Language/framework
- Growth
- Hero deployment
- Scaling

## Communication

- API calls
- Message broker
- Service mesh

## Terms

Message broker
publich/subscribe
point-to-point messaging
pod
service mesh (Kubernetes)
Polyrepo



## Misconceptions

### Programming language

Micro services enable our teams to choose the best programming languages and frameworks for their tasks

Reality: We'll demonstrate just how expensive this is. Team size and investment are critical inputs.

### Codegen is evil

Reality: What's important is creating a defined schema that is 100% trusted. We'll demonstrate one technique leveraging code generation

### Logs as source of truth

The event log must be the source of truth

Reality: Events are critical parts of an interface. But it's okay for services to be the system of record for their resources

### Devs can mantain < 3 services

Developers can maintain no more than 3 services each

Reality: wrong metric, we'll demonstrate where automation shines. Flow developers today each maintain 5 services



## Critical decisions

Design the schema first for all APIs and events (consume events by default)

Invest in automation (deployment, code gen, dependency management)

Enable teams to write amazing and simple tests (quality, streamline maintenance, enable continuous delivery)