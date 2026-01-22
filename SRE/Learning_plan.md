# Go + SRE (Kubernetes, Platform, Identity) — 1 Year Checklist

## Daily Cadence
- [ ] 2h daytime reading (concepts only)
- [ ] 2h evening coding (hands on keyboard)
- [ ] End day with commit + TODO

---

## Quarter 1 — Go Foundations & SRE Primitives

### Week 1 — Go Basics & Tooling
- [ ] Initialize `opsctl` repo
- [ ] Implement `opsctl ping`
- [ ] Structured JSON output
- [ ] Makefile (`build`, `test`)
- [ ] README with run instructions

### Week 2 — Config, Flags, Context
- [ ] Config file support
- [ ] Flag overrides
- [ ] Context-based timeouts
- [ ] Graceful shutdown on SIGINT/SIGTERM

### Week 3 — Concurrency Fundamentals
- [ ] Parallel HTTP checker
- [ ] Concurrency limit
- [ ] Timeout handling
- [ ] Retry with backoff + jitter

### Week 4 — Failure Handling
- [ ] Retry middleware
- [ ] Circuit breaker (basic)
- [ ] Failure simulation mode
- [ ] Clear failure logging

### Week 5 — HTTP Services Correctly
- [ ] HTTP API skeleton
- [ ] Request ID middleware
- [ ] Logging middleware
- [ ] Auth stub middleware
- [ ] Middleware unit tests

### Week 6 — Graceful Services
- [ ] `/healthz` endpoint
- [ ] `/readyz` endpoint
- [ ] Graceful shutdown waits for inflight requests

### Week 7 — Metrics
- [ ] Request counter
- [ ] Latency histogram
- [ ] Error rate metric
- [ ] Prometheus scrape verified

### Week 8 — Tracing
- [ ] Distributed tracing enabled
- [ ] Context propagation
- [ ] Trace IDs in logs

### Week 9 — SLOs
- [ ] Define latency SLO
- [ ] Define error SLO
- [ ] Burn rate alert configured

### Week 10 — OAuth2 Fundamentals
- [ ] Token issuer
- [ ] Token validation middleware
- [ ] Token expiry enforced

### Week 11 — OIDC & JWKS
- [ ] JWKS endpoint
- [ ] Key rotation logic
- [ ] Old tokens still validate

### Week 12 — Identity Hardening
- [ ] Constant-time comparisons
- [ ] Replay protection
- [ ] Audit logs added

### Week 13 — Quarter 1 Review
- [ ] Refactor code
- [ ] Improve docs
- [ ] Architecture diagram
- [ ] Demo-ready

---

## Quarter 2 — Kubernetes & Platform Engineering

### Week 14 — Containers
- [ ] Dockerfile
- [ ] Multi-stage build
- [ ] Image < 50MB
- [ ] No secrets in image

### Week 15 — Kubernetes Basics
- [ ] Deployment manifest
- [ ] Service manifest
- [ ] Probes configured
- [ ] Resource limits set

### Week 16 — Lifecycle Management
- [ ] Init container (if needed)
- [ ] PreStop hook
- [ ] Zero-downtime rollout

### Week 17 — Kubernetes client-go
- [ ] Kubernetes API access
- [ ] Informer-based watch
- [ ] Metrics for events

### Week 18 — Controllers
- [ ] Reconciliation loop
- [ ] Idempotent behavior
- [ ] Error handling

### Week 19 — Controller Hardening
- [ ] Leader election
- [ ] Rate limiting
- [ ] Multi-replica safety

### Week 20 — Workload Identity
- [ ] SPIFFE-style identities
- [ ] Certificate issuance
- [ ] Rotation logic

### Week 21 — mTLS
- [ ] Mutual TLS authentication
- [ ] Unauthorized workload blocked

### Week 22 — Identity Gateway
- [ ] Token verification
- [ ] Policy enforcement
- [ ] Least-privilege access

### Week 23 — Rate Limiting
- [ ] Token bucket or leaky bucket
- [ ] Adaptive rate limits

### Week 24 — Canary Deployments
- [ ] Canary rollout
- [ ] Automated rollback on SLO breach

### Week 25 — Failure Drills
- [ ] Simulated outages
- [ ] Runbooks updated

### Week 26 — Quarter 2 Review
- [ ] Platform stable
- [ ] Ready for chaos testing

---

## Quarter 3 — Security, Incidents, Performance

### Weeks 27–30 — Security
- [ ] Threat model documented
- [ ] Secrets securely injected
- [ ] No secrets in logs
- [ ] Full audit trail

### Weeks 31–34 — Incidents
- [ ] Fault injector implemented
- [ ] Alerts tuned
- [ ] Runbooks complete
- [ ] MTTR < 10 minutes in drills

### Weeks 35–39 — Performance
- [ ] Load testing
- [ ] pprof analysis
- [ ] Hot path optimized
- [ ] p99 latency improved

---

## Quarter 4 — Capstone & Interview Readiness

### Weeks 40–52 — Identity Platform Capstone
- [ ] Identity issuer
- [ ] Token gateway
- [ ] Kubernetes controller
- [ ] Helm charts
- [ ] Dashboards
- [ ] Alerts
- [ ] Incident postmortems

### Final Validation
- [ ] End-to-end demo works
- [ ] Can explain all design tradeoffs
- [ ] Confident with SRE interview questions

