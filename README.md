# Windom Test Agent

Static public documents for a test personal agent. Windom Sports uses it to check its
Personal Agent Protocol sign-in from the outside.

- `agent.json`: the agent's client metadata document (its `client_id` is this file's URL)
- `jwks.json`: its public signing key
- `callback.html`: where sign-in returns the browser; it hands the result to the test runner on the tester's own computer

There is no private data here. The signing key's private half never leaves the tester's computer.
