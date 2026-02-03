# Partner Event Delivery Platform

A production-style backend system for delivering events to external partners with
strong reliability guarantees, schema validation, observability, and AI-assisted
payload diagnostics.

## Goals
- Model a real-world B2B event delivery system
- Demonstrate production-minded system design
- Showcase Kafka-based delivery, failure handling, and observability
- Use AI as a diagnostic and explanation layer, not in the critical path

## High-Level Architecture
See [docs/architecture.md](docs/architecture.md)

## AI Integration
This system uses AI to:
- Validate partner payload templates semantically
- Explain delivery failures in human-readable terms

AI is advisory only and never participates in message delivery.

## Reliability Guarantees
- At-least-once delivery
- Idempotent event handling
- Retry with backoff and dead-letter topics

## Status
🚧 In progress

