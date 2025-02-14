# Transactional Outbox Pattern

A pattern to ensure reliable message publishing in distributed systems:

1. Instead of directly publishing messages/events:
   - Store them in an "outbox" table in the same database as the business data
   - Store them in the same transaction as the business operation
   
2. A separate process/service:
   - Reads the outbox table
   - Publishes the messages to the message broker
   - Marks them as published

This ensures that the business operation and message publishing are atomic, preventing message loss or inconsistency.
