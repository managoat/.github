# Managoat

Coding agents with a real computer behind each one.

- [Fountain](https://github.com/managoat/fountain): run Claude Code, Codex and Gemini CLI as an HTTP API, each on its own sandbox. You can self-host it or [try the apps](https://demo.managoat.com).
- [goatherd](https://github.com/managoat/goatherd): run coding agents in remote sandboxes from your terminal. It needs no server or account.
- [demos](https://github.com/managoat/demos): the Fountain demo suite, small production-shaped apps built on the public API, each at `<name>.demo.managoat.com`.
- [review-loop-action](https://github.com/managoat/review-loop-action): a GitHub Action that starts a PR review loop. The loop reviews, fixes, verifies and approves, but never merges.

## Libraries

- [`managoat_broker`](https://hexdocs.pm/managoat_broker/): an egress proxy that swaps credential placeholders for real credentials at the network boundary, so the sandbox never holds them. Apache-2.0.

`managoat_acp`, `managoat_sandbox`, `managoat_runtimes`, `managoat_oauth`, `managoat_docs`, `managoat_substitution`, `managoat_mcp_auth` and `managoat_runner` are archived. Most were folded back into Fountain, their only consumer. They will get no further releases.
