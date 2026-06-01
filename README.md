# Jonathan Wrede

Platform & Observability Engineer based in Muenster, Germany.

I run production Kubernetes, observability (Prometheus, Grafana, OpenTelemetry), and data/ML platforms at fleet scale, and bring that same production rigor to LLM inference infrastructure.

## What I do

- Production platform and observability: Kubernetes, Helm, ArgoCD, Prometheus, Grafana, OpenTelemetry
- Data/ML platforms at fleet scale: Dagster, dbt, MLflow, Python, Go
- LLM inference infrastructure: llm-d, readiness gates, latency/cost/reliability, benchmarking

## Selected proof

- Sole developer of an end-to-end battery analytics platform for 100,000+ IoT devices: a tested capacity/runtime library, Dagster ingestion, FastAPI services, dashboards, and monitoring, across 8+ repositories.
- 10+ merged infrastructure PRs in [llm-d](https://github.com/llm-d/llm-d-router/pull/1099) (router, inference-sim), [OpenTelemetry](https://github.com/open-telemetry/opentelemetry-python-contrib/pull/4554), and [Feast](https://github.com/feast-dev/feast/pull/6362), with active open contributions in llm-d-kv-cache and llm-d-benchmark.

## Open-source tooling

- [aipreflight](https://github.com/Jwrede/aipreflight): production readiness gate for LLM/RAG services (eval, cost, latency, SLA gates).
- [llmprobe](https://github.com/Jwrede/llmprobe): synthetic monitoring and CI smoke tests for LLM inference endpoints.
- [tokentoll](https://github.com/Jwrede/tokentoll): LLM cost diffs in code review.
- [llm-bench](https://bench.jonathanwrede.de): live benchmark for OpenAI-compatible LLM APIs (TTFT, latency, throughput, errors).

## Writing

- [The missing deployment gate for AI applications](https://jonathanwrede.de/en/blog/the-missing-deployment-gate-for-ai-applications/)
- [Portfolio and CV](https://jonathanwrede.de/en/)
