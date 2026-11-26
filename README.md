# cold-metal
*Exploring the engineering behind AI coding harnesses.*

A hands-on engineering laboratory for understanding, building, evaluating, and deploying LLM-powered systems from first principles. Lightweight by default, measurable by design, scalable when necessary. Frameworks are optional; understanding is not.

A lightweight Python-based coding agent CLI built from scratch and progressively extended into a production-grade system.

## Principles

- **First Principles:** Understand the underlying mechanics before adopting abstractions.
- **Minimal Dependencies:** Introduce dependencies only when they provide meaningful value.
- **Local-First:** Develop and experiment locally whenever possible.
- **Open-Weight First:** Prioritise open-weight models and self-hosted infrastructure.
- **Measurement-Driven:** Benchmark before optimising; validate before claiming improvements.
- **Complexity on Demand:** Introduce architectural complexity only when justified.
- **Learning Over Productisation:** Prioritise engineering knowledge over commercial readiness.
- **Experimentation Over Speculation:** Learn through implementation, observation, and controlled experiments.

## Learning Roadmap

### 1. Agent Harness Engineering

- Framework-free agent loop
- State and session management
- Context engineering and compaction
- Planning, memory, and retries
- Tool calling and MCP integration
- Sandboxing and permission management
- Human-in-the-loop
- Comparative implementation with LangGraph

**Outcome:** A functional coding agent capable of writing, testing, and correcting code autonomously within controlled boundaries.

### 2. Cloud & Production Engineering

- Redis and PostgreSQL
- Message queues
- Distributed workers and systems
- CI/CD
- AWS
- Kubernetes
- Terraform

**Outcome:** A scalable, multi-user, cloud-deployable agent platform with reproducible infrastructure.

### 3. LLM & Agent Evaluation

- SWE-bench and execution-based evaluation
- Agent trajectory analysis
- Langfuse and OpenTelemetry
- Regression testing
- LLM-as-a-judge
- Guardrails

**Outcome:** A reproducible evaluation and observability infrastructure for measuring agent reliability, performance, and behavioural improvements.

### 4. LLM Inference & Serving

- vLLM and SGLang
- Continuous batching
- KV cache and prefix caching
- Quantisation
- Throughput, TTFT, and TPOT
- Model routing and LiteLLM
- GPU memory management

**Outcome:** A self-hosted inference infrastructure capable of serving, benchmarking, and optimising open-weight LLMs.

### 5. Knowledge Engineering

- Ontology design
- Knowledge graphs
- RDF, OWL, and SPARQL
- Neo4j and Cypher
- AST and Tree-sitter
- Semantic code indexing
- Entity and relationship extraction
- GraphRAG

**Outcome:** A structured repository understanding system that enables the agent to reason over code relationships, dependencies, and semantic context.

### 6. Open-Ended Experimentation

Once the foundational roadmap is complete, Cold Metal transitions into an open-ended experimentation laboratory for exploring emerging AI engineering techniques, architectures, tools, and research findings.

New approaches are implemented, benchmarked, and compared against existing baselines. Successful experiments may be integrated into Pilav where they provide measurable value.

No fixed roadmap beyond the foundations. Curiosity drives what comes next.

Add durations to every roadmap stageClarify the roadmap’s stage dependencies
