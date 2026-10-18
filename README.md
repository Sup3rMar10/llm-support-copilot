# llm-support-copilot

Offline, deterministic, stdlib-only support copilot for a fictional SaaS ("Nimbus Cloud"): BM25 retrieval, gated tools, agent loop, guardrails, tracing, HTTP API.
Work in progress: evals, regression gate, load test and the full write-up are added in phase 2.
Run the tests with `python -m pytest`; try it with `python -m copilot ask "how do I reset my password"`.
The `ClaudeModel` adapter is untested against the live API (fake transport only); all data is synthetic.
License: MIT.
