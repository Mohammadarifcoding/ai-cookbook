# Backend, AI Engineering & FDE Roadmap

> Track progress with the proficiency scale below. Fill in a level (0-5) next to each skill as you go.

## Proficiency Scale

| Level | Meaning |
|---|---|
| 0 | Not learned |
| 1 | Understand the concept |
| 2 | Can implement with guidance |
| 3 | Can implement independently |
| 4 | Can design and operate production systems |
| 5 | Can debug, optimize, make tradeoffs, and teach others |

**Target:** Core capabilities → Level 4-5. Supporting tech → Level 2-3. Optional tech → Level 1 until needed.

---

## Learning Priority (Phases)

- [ ] **Phase 1** — Foundations: Software eng basics → Backend eng → PostgreSQL/Redis → AuthN/AuthZ → Testing
- [ ] **Phase 2** — Distributed systems: Workflows → Queues → Idempotency → Caching → Docker → CI/CD → Observability
- [ ] **Phase 3** — AI core: Model APIs → Structured outputs → Context engineering → Tool calling → RAG
- [ ] **Phase 4** — Agentic systems: Agent workflows → State → Harness engineering → Human approval → Durable workflows → AI eval
- [ ] **Phase 5** — Production & scale: AI security → Enterprise integrations → Multi-tenant architecture → FDE skills → Production AI systems

---

## Table of Contents

1. [Software Engineering Foundations](#01-software-engineering-foundations)
2. [Backend and API Engineering](#02-backend-and-api-engineering)
3. [Database and Data Engineering](#03-database-and-data-engineering)
4. [Distributed Systems and Workflow Engineering](#04-distributed-systems-and-workflow-engineering)
5. [Testing and Software Quality](#05-testing-and-software-quality)
6. [Cloud, DevOps and Production Engineering](#06-cloud-devops-and-production-engineering)
7. [Observability, Reliability and Operations](#07-observability-reliability-and-operations)
8. [Security and Compliance](#08-security-and-compliance)
9. [AI Application Engineering](#09-ai-application-engineering)
10. [Retrieval and RAG](#10-retrieval-and-rag)
11. [Agentic Systems](#11-agentic-systems)
12. [AI Evaluation, Safety and Operations](#12-ai-evaluation-safety-and-operations)
13. [Enterprise Integration Engineering](#13-enterprise-integration-engineering)
14. [Forward Deployed Engineering](#14-forward-deployed-engineering-and-product-delivery)
15. [Product Building and Frontend Breadth](#15-product-building-and-frontend-breadth)
16. [AI Assisted Software Engineering](#16-ai-assisted-software-engineering)
17. [Document and Multimodal AI](#17-document-and-multimodal-ai)
18. [Desktop and Offline Systems](#18-desktop-and-offline-systems)
19. [Advanced Specialization](#19-advanced-specialization)
20. [Interview Preparation](#20-interview-preparation)

---

## 01. Software Engineering Foundations

### Programming
| Skill | Level (0-5) |
|---|---|
| TypeScript | |
| Node.js | |
| Python for AI engineering | |
| Data structures fundamentals | |
| Object oriented programming | |
| Functional programming fundamentals | |
| Error handling | |
| Dependency management | |

### Runtime Fundamentals
| Skill | Level (0-5) |
|---|---|
| Processes | |
| Threads | |
| Event loop | |
| Asynchronous programming | |
| Concurrency | |
| Parallelism fundamentals | |
| Memory fundamentals | |
| Filesystem fundamentals | |
| Streams | |
| Buffers | |

### Operating Systems
| Skill | Level (0-5) |
|---|---|
| Linux | |
| Shell usage | |
| Processes and signals | |
| Permissions | |
| Environment variables | |
| Filesystem navigation | |
| Resource monitoring | |

### Networking
| Skill | Level (0-5) |
|---|---|
| HTTP | |
| HTTPS | |
| TCP and UDP fundamentals | |
| DNS | |
| Ports | |
| Proxies | |
| Reverse proxies | |
| TLS fundamentals | |
| WebSockets fundamentals | |

### Developer Workflow
| Skill | Level (0-5) |
|---|---|
| Git | |
| Branching strategies | |
| Debugging | |
| Profiling | |
| Static analysis | |
| Package management | |
| Code review | |
| Refactoring | |

---

## 02. Backend and API Engineering

> Learning direction: `HTTP → API design → validation → authentication → authorization → multi tenancy`

### API Engineering
| Skill | Level (0-5) |
|---|---|
| REST API design | |
| Resource modeling | |
| Request validation | |
| Response design | |
| Error response design | |
| Pagination | |
| Filtering | |
| Sorting | |
| API versioning | |
| OpenAPI | |
| API documentation | |
| File uploads | |
| WebSockets fundamentals | |

### Authentication
| Skill | Level (0-5) |
|---|---|
| Password security | |
| Session management | |
| Cookies | |
| JWT | |
| Refresh tokens | |
| OAuth 2.0 | |
| OpenID Connect | |
| SSO fundamentals | |
| SAML fundamentals | |
| MFA fundamentals | |

### Authorization
| Skill | Level (0-5) |
|---|---|
| Permissions | |
| RBAC | |
| ABAC | |
| Policy based authorization | |
| Resource ownership | |
| Tenant scoped permissions | |

### Multi Tenancy
| Skill | Level (0-5) |
|---|---|
| Multi tenant architecture | |
| Tenant identification | |
| Tenant isolation | |
| Database isolation strategies | |
| Authorization isolation | |
| Storage isolation | |
| Cross tenant attack prevention | |
| Tenant aware background jobs | |
| Tenant aware caching | |

---

## 03. Database and Data Engineering

> Rule: `PostgreSQL first → specialized database second`

### Relational Databases
| Skill | Level (0-5) |
|---|---|
| Relational modeling | |
| PostgreSQL | |
| SQL | |
| Schema design | |
| Relationships | |
| Constraints | |
| Transactions | |
| ACID | |
| Isolation levels | |
| Locks | |
| Indexes | |
| Query plans | |
| Query optimization | |
| Connection pooling | |
| Migrations | |

### Database Operations
| Skill | Level (0-5) |
|---|---|
| Backups | |
| Restore testing | |
| Replication fundamentals | |
| Database monitoring | |
| Data migrations | |
| Zero downtime migration fundamentals | |

### Redis
| Skill | Level (0-5) |
|---|---|
| Redis fundamentals | |
| Caching | |
| Cache invalidation | |
| TTL strategies | |
| Distributed coordination fundamentals | |
| Rate limit storage | |
| Queue backing storage | |

### Data Processing
| Skill | Level (0-5) |
|---|---|
| CSV import and export | |
| Excel processing | |
| Data validation | |
| Data cleaning | |
| Data mapping | |
| Schema transformation | |
| Reconciliation | |
| Analytics queries | |
| Reporting tables | |

### Specialized Databases *(learn only when required)*
| Skill | Level (0-5) |
|---|---|
| pgvector | |
| Qdrant | |
| Vector databases | |
| Neo4j | |
| Cypher | |
| Graph databases | |
| Data warehouses | |

---

## 04. Distributed Systems and Workflow Engineering

> Learning direction: `Background jobs → queues → retries → idempotency → outbox → events → durable workflows`

### Background Processing
| Skill | Level (0-5) |
|---|---|
| Background workers | |
| Queue fundamentals | |
| Job processing | |
| Scheduled jobs | |
| Delayed jobs | |
| Job priorities | |

### Reliability
| Skill | Level (0-5) |
|---|---|
| Retry strategies | |
| Exponential backoff | |
| Idempotency | |
| Deduplication | |
| Timeouts | |
| Cancellation | |
| Dead letter queues | |
| Poison messages | |

### Distributed Coordination
| Skill | Level (0-5) |
|---|---|
| Distributed locking | |
| Leader election fundamentals | |
| Outbox pattern | |
| Inbox pattern | |
| Event driven architecture | |
| Eventual consistency | |
| Saga fundamentals | |

### Durable Workflows
| Skill | Level (0-5) |
|---|---|
| Durable execution | |
| Workflow state | |
| Workflow recovery | |
| Checkpointing | |
| Long running workflows | |
| Human approval workflows | |

### Resilience
| Skill | Level (0-5) |
|---|---|
| Backpressure | |
| Circuit breakers | |
| Bulkheads | |
| Graceful degradation | |
| Failure isolation | |
| Dependency failure handling | |

---

## 05. Testing and Software Quality

> Keep normal software testing separate from AI evaluation.

### Core Testing
| Skill | Level (0-5) |
|---|---|
| Unit testing | |
| API testing | |
| Integration testing | |
| End to end testing | |
| Contract testing | |
| Database testing | |
| Migration testing | |
| Permission testing | |
| Regression testing | |

### Production Quality
| Skill | Level (0-5) |
|---|---|
| Load testing | |
| Stress testing | |
| Performance testing | |
| Static analysis | |
| Dependency scanning | |
| Security testing | |
| Code review | |
| Refactoring | |
| Testable architecture | |

---

## 06. Cloud, DevOps and Production Engineering

### Containers
| Skill | Level (0-5) |
|---|---|
| Docker | |
| Dockerfiles | |
| Container networking | |
| Container volumes | |
| Docker Compose | |
| Container security | |

### Configuration
| Skill | Level (0-5) |
|---|---|
| Environment management | |
| Secret management | |
| Configuration validation | |
| Secret rotation | |

### Delivery
| Skill | Level (0-5) |
|---|---|
| CI/CD | |
| GitHub Actions | |
| Automated testing | |
| Automated deployment | |
| Rollback strategies | |
| Feature flags | |
| Blue green deployment | |
| Canary deployment | |

### Infrastructure
| Skill | Level (0-5) |
|---|---|
| Infrastructure as Code | |
| Terraform | |
| Cloud IAM | |
| Cloud networking | |
| VPC fundamentals | |
| Load balancers | |
| Reverse proxies | |
| Domains | |
| DNS | |
| TLS certificates | |

### Deployment
| Skill | Level (0-5) |
|---|---|
| Server deployment | |
| Container deployment | |
| Serverless fundamentals | |
| Database deployment | |
| Development environment | |
| Staging environment | |
| Production environment | |

### Cloud Strategy
| Skill | Level (0-5) | Depth |
|---|---|---|
| One cloud provider (choose one) | | Deep |
| AWS | | General awareness |
| Azure | | General awareness |
| GCP | | General awareness |

### Kubernetes *(fundamentals first)*
| Skill | Level (0-5) |
|---|---|
| Pods | |
| Deployments | |
| Services | |
| ConfigMaps | |
| Secrets | |
| Ingress | |
| Scaling | |

### Cost Engineering
| Skill | Level (0-5) |
|---|---|
| Cloud cost awareness | |
| Resource sizing | |
| Storage cost | |
| Database cost | |
| AI API cost | |
| Cost monitoring | |

---

## 07. Observability, Reliability and Operations

> Learning direction: `Logs → metrics → traces → alerts → SLO → incident response`

### Observability
| Skill | Level (0-5) |
|---|---|
| Structured logging | |
| Metrics | |
| Distributed tracing | |
| OpenTelemetry | |
| Correlation IDs | |
| Dashboards | |

### Monitoring
| Skill | Level (0-5) |
|---|---|
| Alerting | |
| Health checks | |
| Readiness checks | |
| Liveness checks | |
| Availability measurement | |
| Latency measurement | |
| Error rate measurement | |

### Reliability Engineering
| Skill | Level (0-5) |
|---|---|
| SLI | |
| SLO | |
| Error budgets | |
| Capacity planning | |
| Scaling strategy | |

### Incident Management
| Skill | Level (0-5) |
|---|---|
| Incident response | |
| Runbooks | |
| Production incident communication | |
| Root cause analysis | |
| Postmortems | |
| Post deployment support | |

### Disaster Recovery
| Skill | Level (0-5) |
|---|---|
| Backup strategy | |
| RPO | |
| RTO | |
| Disaster recovery | |
| Restore drills | |

---

## 08. Security and Compliance

### Application Security
| Skill | Level (0-5) |
|---|---|
| OWASP fundamentals | |
| Threat modeling | |
| Secure input validation | |
| Secure output handling | |
| Authentication security | |
| Authorization security | |
| Session security | |
| CSRF | |
| XSS | |
| SQL injection | |
| SSRF | |
| File upload security | |

### Infrastructure Security
| Skill | Level (0-5) |
|---|---|
| Encryption in transit | |
| Encryption at rest | |
| IAM | |
| Least privilege | |
| Credential rotation | |
| Secret management | |
| Secure dependency management | |
| Software supply chain security | |
| SBOM fundamentals | |

### API Security
| Skill | Level (0-5) |
|---|---|
| Rate limiting | |
| Webhook signatures | |
| Replay attack prevention | |
| API key management | |
| Token rotation | |

### Data Protection
| Skill | Level (0-5) |
|---|---|
| PII handling | |
| Sensitive data classification | |
| Audit logs | |
| Data retention | |
| Data deletion | |
| Data minimization | |
| GDPR fundamentals | |
| DPA fundamentals | |

---

## 09. AI Application Engineering

> Learning direction: `Model APIs → structured output → context engineering → tool use → routing → production constraints`

### LLM Fundamentals
| Skill | Level (0-5) |
|---|---|
| Transformer fundamentals | |
| Tokens | |
| Context windows | |
| Model capabilities | |
| Model limitations | |
| Reasoning models | |
| Multimodal models | |

### Model APIs
| Skill | Level (0-5) |
|---|---|
| Model API usage | |
| Streaming | |
| Structured outputs | |
| Schema constrained generation | |
| Function calling | |
| Error handling | |
| Retry handling | |

### Prompt and Context Engineering
| Skill | Level (0-5) |
|---|---|
| Prompt engineering | |
| System instructions | |
| Context engineering | |
| Context prioritization | |
| Context compression | |
| Context window management | |

### Model Strategy
| Skill | Level (0-5) |
|---|---|
| Model selection | |
| Model routing | |
| Provider abstraction | |
| Provider fallback | |
| Cost optimization | |
| Latency optimization | |
| Token management | |
| Prompt caching | |

### Local Models
| Skill | Level (0-5) |
|---|---|
| Ollama | |
| Local model fundamentals | |
| Privacy considerations | |
| Local inference tradeoffs | |

---

## 10. Retrieval and RAG

> Capability first. Technology second.

### Retrieval Fundamentals
| Skill | Level (0-5) |
|---|---|
| Embeddings | |
| Similarity search | |
| Vector retrieval | |
| Keyword retrieval | |
| Hybrid retrieval | |

### Data Ingestion
| Skill | Level (0-5) |
|---|---|
| Document ingestion | |
| Parsing | |
| Chunking | |
| Metadata design | |
| Embedding pipelines | |
| Indexing pipelines | |
| Incremental indexing | |

### Retrieval Quality
| Skill | Level (0-5) |
|---|---|
| Metadata filtering | |
| Query rewriting | |
| Reranking | |
| Retrieval evaluation | |
| Relevance measurement | |

### Production RAG
| Skill | Level (0-5) |
|---|---|
| Permission aware retrieval | |
| Tenant aware retrieval | |
| Citation generation | |
| Source attribution | |
| RAG observability | |
| Index updates | |
| Retrieval caching | |

### RAG Security
| Skill | Level (0-5) |
|---|---|
| RAG poisoning defense | |
| Prompt injection through retrieved documents | |
| Cross tenant retrieval prevention | |
| Sensitive document filtering | |

### Implementation Technologies
| Skill | Level (0-5) |
|---|---|
| pgvector | |
| Qdrant | |
| Elasticsearch | |
| Other vector stores | |

---

## 11. Agentic Systems

> Learning direction: `Tool calling → controlled workflows → state → memory → approval → durable agents → multi agent systems`

### Tool Use
| Skill | Level (0-5) |
|---|---|
| Tool calling | |
| Tool schema design | |
| Tool input validation | |
| Tool output validation | |
| Tool errors | |
| Tool permissions | |
| Tool isolation | |

### Agent Architecture
| Skill | Level (0-5) |
|---|---|
| Agent loops | |
| Agent state | |
| Memory | |
| Working memory | |
| Persistent memory | |
| Planning fundamentals | |
| Termination conditions | |

### Workflow Orchestration
| Skill | Level (0-5) |
|---|---|
| Deterministic workflows | |
| Agentic workflows | |
| Workflow state | |
| Checkpointing | |
| Human approval | |
| Approval boundaries | |
| Escalation | |
| Failure recovery | |

### Agent Harness Engineering
| Skill | Level (0-5) |
|---|---|
| Context management | |
| Tool registry | |
| Execution environment | |
| Filesystem access | |
| Code execution | |
| State persistence | |
| Checkpointing | |
| Retry policies | |
| Budget controls | |
| Permission boundaries | |
| Termination logic | |
| Subagent coordination | |

### Agent Protocols and Frameworks
| Skill | Level (0-5) |
|---|---|
| MCP | |
| MCP clients | |
| MCP servers | |
| MCP authorization | |
| LangGraph | |
| Agent framework fundamentals | |

### Advanced Agents
| Skill | Level (0-5) |
|---|---|
| Durable agents | |
| Long running agents | |
| Multi agent systems | |
| Agent delegation | |
| Subagents | |

---

## 12. AI Evaluation, Safety and Operations

> Learning direction: `Golden dataset → offline evaluation → regression evaluation → production monitoring → red teaming`

### Evaluation Datasets
| Skill | Level (0-5) |
|---|---|
| Golden datasets | |
| Dataset versioning | |
| Evaluation dataset management | |
| Representative test cases | |
| Edge cases | |

### AI Evaluation
| Skill | Level (0-5) |
|---|---|
| Offline evaluation | |
| Online evaluation | |
| Regression evaluation | |
| Retrieval evaluation | |
| Tool use evaluation | |
| Task completion evaluation | |
| Hallucination testing | |
| Structured output evaluation | |

### Evaluation Methods
| Skill | Level (0-5) |
|---|---|
| Deterministic evaluation | |
| Human evaluation | |
| LLM as judge | |
| Judge calibration | |
| LLM judge limitations | |

### AI Observability
| Skill | Level (0-5) |
|---|---|
| Prompt monitoring | |
| Model monitoring | |
| Prompt versioning | |
| Model version tracking | |
| Cost tracking | |
| Token tracking | |
| Latency tracking | |
| Task success tracking | |

### AI Safety
| Skill | Level (0-5) |
|---|---|
| Prompt injection defense | |
| Indirect prompt injection | |
| Sensitive data disclosure prevention | |
| Guardrails | |
| PII detection | |
| PII redaction | |
| Low confidence escalation | |
| Human approval | |

### AI Security
| Skill | Level (0-5) |
|---|---|
| Tool abuse prevention | |
| Excessive agency prevention | |
| Context poisoning | |
| Memory poisoning | |
| Retrieval poisoning | |
| Tool privilege escalation | |
| MCP security | |
| Model supply chain security | |
| Data supply chain security | |
| AI red teaming | |

---

## 13. Enterprise Integration Engineering

### APIs
| Skill | Level (0-5) |
|---|---|
| Third party APIs | |
| OAuth integrations | |
| API keys | |
| External authentication | |
| External rate limits | |

### Communication Patterns
| Skill | Level (0-5) |
|---|---|
| Webhooks | |
| Polling | |
| Event subscriptions | |
| Webhook retries | |
| Webhook deduplication | |

### Enterprise Systems
| Skill | Level (0-5) |
|---|---|
| CRM integration | |
| ERP integration | |
| Payroll systems | |
| Document stores | |
| Data warehouses | |
| Identity providers | |
| Legacy systems | |

### Data Integration
| Skill | Level (0-5) |
|---|---|
| Schema transformation | |
| Data mapping | |
| Data reconciliation | |
| Data validation | |
| Import pipelines | |
| Export pipelines | |

### Connector Architecture
| Skill | Level (0-5) |
|---|---|
| Connector abstractions | |
| Connector authentication | |
| Connector configuration | |
| Connector retries | |
| Connector observability | |
| Connector failure recovery | |
| Connector versioning | |

---

## 14. Forward Deployed Engineering and Product Delivery

> Learning direction: `Discovery → problem framing → requirements → prototype → pilot → production → adoption → handover`

### Discovery
| Skill | Level (0-5) |
|---|---|
| Customer discovery | |
| Stakeholder interviews | |
| Manual workflow analysis | |
| Business process understanding | |
| Domain understanding | |
| Pain point identification | |

### Requirements
| Skill | Level (0-5) |
|---|---|
| Problem framing | |
| Requirement discovery | |
| Requirement clarification | |
| Functional requirements | |
| Non functional requirements | |
| Must have vs nice to have | |
| Acceptance criteria | |

### Solution Design
| Skill | Level (0-5) |
|---|---|
| Domain modeling | |
| Automation opportunity identification | |
| Architecture whiteboarding | |
| Architecture explanation | |
| Technical tradeoff communication | |
| Risk analysis | |

### Delivery
| Skill | Level (0-5) |
|---|---|
| Rapid prototyping | |
| Demo engineering | |
| MVP scoping | |
| Pilot design | |
| Integration design | |
| Deployment ownership | |

### Business Outcomes
| Skill | Level (0-5) |
|---|---|
| KPI definition | |
| ROI estimation | |
| Adoption measurement | |
| Success criteria | |

### Communication
| Skill | Level (0-5) |
|---|---|
| Stakeholder communication | |
| Executive communication | |
| Technical communication | |
| Documentation | |
| Knowledge transfer | |
| Customer handover | |

### Production Ownership
| Skill | Level (0-5) |
|---|---|
| Production support | |
| Incident handling | |
| Customer feedback | |
| Iteration after deployment | |

---

## 15. Product Building and Frontend Breadth

### Frontend Engineering
| Skill | Level (0-5) |
|---|---|
| React | |
| Next.js | |
| TypeScript | |
| Component architecture | |
| State management | |
| Data fetching | |

### Product UI
| Skill | Level (0-5) |
|---|---|
| Forms | |
| Validation | |
| Authentication UI | |
| Role based UI | |
| Permission aware UI | |
| Dashboard design | |
| Tables | |
| Search | |
| Filtering | |
| Pagination | |

### UX Quality
| Skill | Level (0-5) |
|---|---|
| Loading states | |
| Error states | |
| Empty states | |
| Responsive design | |
| Accessibility | |
| Performance fundamentals | |

### Product Learning
| Skill | Level (0-5) |
|---|---|
| Product analytics | |
| Event tracking | |
| User feedback collection | |
| Feature adoption measurement | |

---

## 16. AI Assisted Software Engineering

> Core rule: `AI writes faster → engineer verifies harder`

### AI Development Workflow
| Skill | Level (0-5) |
|---|---|
| AI coding assistants | |
| Coding agents | |
| Repository context management | |
| Project instruction files | |
| Specification driven development | |
| Task decomposition | |

### AI Assisted Implementation
| Skill | Level (0-5) |
|---|---|
| Code generation | |
| Refactoring | |
| Debugging | |
| Test generation | |
| Documentation generation | |
| Migration assistance | |

### Verification
| Skill | Level (0-5) |
|---|---|
| AI generated code review | |
| Correctness verification | |
| Security verification | |
| Test verification | |
| Dependency verification | |

### Agentic Coding
| Skill | Level (0-5) |
|---|---|
| Parallel coding agents | |
| Task delegation | |
| Repository scoped agents | |
| Agent review workflows | |
| Human review boundaries | |

---

## 17. Document and Multimodal AI

### Documents
| Skill | Level (0-5) |
|---|---|
| PDF processing | |
| OCR | |
| Layout extraction | |
| Table extraction | |
| Form extraction | |
| Document classification | |
| Structured data extraction | |

### Multimodal Systems
| Skill | Level (0-5) |
|---|---|
| Image understanding | |
| Vision models | |
| Document vision | |
| Image plus text workflows | |

### Production Document AI
| Skill | Level (0-5) |
|---|---|
| Confidence scoring | |
| Validation rules | |
| Human review | |
| Document provenance | |
| Extraction auditability | |
| Reprocessing | |
| Document versioning | |

---

## 18. Desktop and Offline Systems

> Breadth track only. Do not let this block backend or AI progression.

### Desktop
| Skill | Level (0-5) |
|---|---|
| Electron or Tauri | |
| Desktop architecture | |
| Operating system integration | |
| Application packaging | |
| Code signing | |
| Automatic updates | |
| Crash reporting | |

### Local Data
| Skill | Level (0-5) |
|---|---|
| SQLite | |
| IndexedDB fundamentals | |
| Local persistence | |
| Secure local storage | |
| Local encryption | |
| Secure credential storage | |

### Offline Systems
| Skill | Level (0-5) |
|---|---|
| Offline first architecture | |
| Offline queues | |
| Synchronization | |
| Conflict resolution | |
| Optimistic updates | |
| Reconnection strategies | |

### Local AI
| Skill | Level (0-5) |
|---|---|
| Local model execution | |
| Local embeddings | |
| Offline inference | |

---

## 19. Advanced Specialization

> Learn when your work demands it. None of these should block your core roadmap.

### Distributed Systems
| Skill | Level (0-5) |
|---|---|
| Advanced distributed systems | |
| Consensus fundamentals | |
| Distributed databases | |

### Infrastructure
| Skill | Level (0-5) |
|---|---|
| Advanced Kubernetes | |
| Advanced networking | |
| Platform engineering | |

### Security
| Skill | Level (0-5) |
|---|---|
| Advanced application security | |
| Cloud security | |
| Security engineering | |

### AI Infrastructure
| Skill | Level (0-5) |
|---|---|
| Model serving | |
| Fine tuning | |
| GPU fundamentals | |
| Quantization | |
| High performance inference | |
| Model optimization | |

### Advanced Retrieval
| Skill | Level (0-5) |
|---|---|
| GraphRAG | |
| Knowledge graphs | |
| Advanced retrieval architectures | |

### Languages
| Skill | Level (0-5) |
|---|---|
| Go | |
| Rust | |

---

## 20. Interview Preparation

> Keep this separate from engineering competency.

### Algorithms
| Skill | Level (0-5) |
|---|---|
| Arrays | |
| Strings | |
| Hash maps | |
| Linked lists | |
| Stacks | |
| Queues | |
| Trees | |
| Graphs | |
| BFS | |
| DFS | |
| Heaps | |
| Binary search | |
| Recursion | |
| Dynamic programming | |

### Interviews
| Skill | Level (0-5) |
|---|---|
| Coding exercises | |
| Backend interviews | |
| System design interviews | |
| AI system design interviews | |
| Behavioral interviews | |
| Customer scenarios | |
| Architecture discussions | |

---

## Reference: Parent Capability Rule

Frameworks/tools are implementations, not primary skills. Learn the capability; treat the tool as swappable.

```
Agent orchestration
├── Tool calling
├── State
├── Memory
├── Human approval
├── Recovery
├── Durable workflows
├── MCP
└── LangGraph (implementation)

Vector retrieval
├── Embeddings
├── Chunking
├── Metadata
├── Filtering
├── Hybrid search
├── Reranking
├── pgvector (implementation)
└── Qdrant (implementation)

Queue processing
├── Jobs
├── Retries
├── Idempotency
├── Scheduling
├── Dead letter queues
├── BullMQ / SQS / RabbitMQ (implementations)
```

---

## Reference: 8 Main Career Capability Groups

1. Software Engineering Foundations
2. Backend and Data Engineering
3. Distributed Systems and Reliability
4. Cloud, Security and Production
5. AI Application Engineering
6. Agentic Systems and Evaluation
7. Enterprise Integration Engineering
8. Forward Deployed Product Engineering

---

## Reference: Mastery Targets

### Deep mastery (Level 4+)
TypeScript, Node.js, Backend architecture, HTTP, PostgreSQL, SQL, Redis, API design, Authentication, Authorization, Multi tenancy, Queues, Distributed workflows, Docker, CI/CD, Observability, Security fundamentals, LLM APIs, Structured outputs, Tool calling, RAG, Agent orchestration, AI evaluation, Enterprise integrations, FDE delivery skills

### Working knowledge (Level 2-3)
Terraform, Kubernetes, Neo4j, Qdrant, SAML, GraphRAG, Desktop development, Local models, Advanced cloud networking, Data warehouses

### Optional specialization (only with clear demand)
Rust, Go, GPU programming, Fine tuning, Quantization, Advanced Kubernetes, Advanced distributed systems, High performance inference, Deep ML research

---

## North Star

> Optimize for: **What kinds of real problems can I independently understand, design, build, secure, deploy, evaluate and operate?**

`Strong software engineer + Strong backend engineer + Production AI engineer + Enterprise integration engineer + Product minded FDE`
