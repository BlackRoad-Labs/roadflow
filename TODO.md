# RoadFlow — TODO

## [RC] Core Engine
- [ ] [RC] Fork and customize OverPass (n8n) engine
- [ ] [RC] Implement visual canvas with snap-to-grid
- [ ] [RC] Build node execution runtime
- [ ] [RC] Add cron scheduler with expression parser
- [ ] [RC] Implement webhook trigger endpoint
- [ ] [RC] Build credential vault with AES-256 encryption
- [ ] [RC] Add execution history with full I/O logging

## [RC] Node Library
- [ ] [RC] HTTP Request node (REST, GraphQL, SOAP)
- [ ] [RC] PostgreSQL node (query, insert, update, delete)
- [ ] [RC] Redis node (get, set, pub/sub, streams)
- [ ] [RC] Email node (SMTP send, IMAP receive)
- [ ] [RC] SSH node (remote command execution)
- [ ] [RC] File system node (read, write, watch)
- [ ] [RC] MinIO/S3 node (object storage operations)
- [ ] [RC] MQTT node (IoT pub/sub)
- [ ] [RC] Git node (clone, commit, push, PR)
- [ ] [RC] Docker node (container management)

## [RC] AI Nodes
- [ ] [RC] Ollama integration node (local inference)
- [ ] [RC] OpenAI-compatible endpoint node
- [ ] [RC] Embedding generation node
- [ ] [RC] Text classification node
- [ ] [RC] Summarization node
- [ ] [RC] RAG (retrieval-augmented generation) node

## [RC] Pi Fleet Integration
- [ ] [RC] Pi discovery and SSH management
- [ ] [RC] Sensor data collection nodes
- [ ] [RC] Service deployment nodes
- [ ] [RC] WireGuard mesh status nodes
- [ ] [RC] RoundTrip agent messaging node

## [RC] Workflow Features
- [ ] [RC] Conditional branching with boolean logic
- [ ] [RC] Loop and iterator nodes
- [ ] [RC] Sub-workflow composition
- [ ] [RC] Error handling with retry and fallback
- [ ] [RC] Dead letter queue for failed items
- [ ] [RC] Workflow versioning and rollback

## [RC] Infrastructure
- [ ] [RC] Single binary build (Go or Rust)
- [ ] [RC] Docker image with ARM support
- [ ] [RC] Landing page deployment to roadflow.blackroad.io
- [ ] [RC] CI/CD pipeline
- [ ] [RC] SQLite default storage engine
- [ ] [RC] PostgreSQL storage option for scale
