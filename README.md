# Event-Driven System Integration

## Problem
Modern businesses use multiple disconnected systems (messaging, CRM, scheduling).
These systems do not communicate in real time, causing lost data and manual work.

## Requirements
- Real-time processing
- Event-driven communication
- API-based integration
- Fault tolerance
- Secure credential handling

## Solution
I designed an event-driven architecture using webhooks and APIs
to orchestrate communication between systems.

Inbound Event
→ Orchestration Layer
→ Business Logic
→ External Services
→ Observability

## Architecture
(Architecture diagram here)

## Technical Decisions
- Webhooks instead of polling to reduce latency
- Stateless execution for scalability
- Centralized orchestration for better observability
- Separation of concerns between logic and integrations

## Cloud Concepts Demonstrated
- Event-driven architecture
- REST APIs
- Authentication & secrets management
- Asynchronous workflows
- Error handling and retries

## Trade-offs & Improvements
- Replace orchestration layer with AWS Step Functions
- Add message queue (SQS) for higher throughput
- Centralized logging with CloudWatch

- <img width="721" height="321" alt="ORCHESTRATION" src="https://github.com/user-attachments/assets/b6daeef9-af38-438e-a40c-2aba165c3d47" />

![8E35F1F9-A66F-4D3C-BAC4-5DDFEEB1B4F6](https://github.com/user-attachments/assets/e5f49ce5-3105-42fe-b0d8-11a01b81b6d2)


