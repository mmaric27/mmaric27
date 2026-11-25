# Marko Marić

**Senior Backend Engineer | Data Modelling, Integrations & Reliability**

I work on business-critical systems where the data model, the integration contract and the behaviour in production all have to agree. Most of that work is in private repositories. Here are a few public examples you can inspect.

### [Integration Ops](https://github.com/mmaric27/integration-ops)

What should happen when the same request arrives twice, or a worker stops halfway through a job?

Integration Ops is my personal reference implementation of idempotent request intake and durable background processing in .NET and PostgreSQL, with a React UI. The code, integration tests and architecture decision records show how leases, bounded retries and recovery fit together.

### [Engineering Notes](https://github.com/mmaric27/engineering-notes)

Short technical notes on safe SQL migrations, production diagnostics, source-control modernization and integration design. For an example that connects architecture with AI tooling, start with [Protocol-neutral capability layers for AI channels](https://github.com/mmaric27/engineering-notes/blob/main/architecture/protocol-neutral-capability-layers-for-ai-channels.md).

### Open-source fixes

Four merged fixes in AI developer tooling, each with a regression test:

- [Acode AI Agent #4](https://github.com/Acode-Foundation/acode-ai-agent/pull/4): Made queued credential changes respect cancellation without breaking their execution order.
- [Acode AI Agent Plugin #8](https://github.com/hallofcodes/acode-ai-agent-plugin/pull/8): Fixed an Ollama streaming bug where a network chunk could split a single NDJSON record.
- [Acode AI Agent Plugin #9](https://github.com/hallofcodes/acode-ai-agent-plugin/pull/9): Stopped new tools from being dispatched after cancellation.
- [Acode AI Agent Plugin #10](https://github.com/hallofcodes/acode-ai-agent-plugin/pull/10): Fixed streaming when the caller does not supply an `AbortSignal`.

I use AI as leverage, not as a substitute for engineering judgment. I define the problem, direct the work, review changes and verify results.

[LinkedIn](https://www.linkedin.com/in/mark-om42/)
