# Saga Patterns

Sagas are a pattern for managing distributed transactions through a sequence of local transactions.

## Types of Sagas

### 1. Choreography
- Each service publishes events that trigger operations in other services
- Decentralized approach
- Services react to events from other services
- Better for simple flows

### 2. Orchestration
- Central coordinator (orchestrator) that directs the transaction steps
- Centralized control flow
- Orchestrator manages the entire transaction
- Better for complex flows with many participants
