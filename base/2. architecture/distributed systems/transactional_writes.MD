# Transactional Writes in Distributed Systems

When implementing transactional writes across multiple systems in a distributed environment:

1. Clearly define and separate your system boundaries
2. Implement distributed transactions using either:
   - Saga patterns (see: sagas.MD)
   - Transactional Outbox pattern (see: transactional_outbox.MD)
