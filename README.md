# Perture for v0

Connect v0 to Perture through its bring-your-own MCP connection.

## Connect

1. Open a v0 chat or the MCP Connections settings page.
2. Select `Add MCP` and choose a custom server.
3. Use `Perture` as the name and `https://app.perture.co/mcp` as the server URL.
4. Select OAuth and complete the Perture sign-in.

An owner with an active Pro plan can explicitly ask v0 to edit Brand Page
colors, typography, logos, fonts, illustrations, spacing and rounding through
the Perture MCP tools. Every edit requires the selected brand and its lock.
Reconnect an existing read-only connection and approve the displayed write
scopes to use these tools; old tokens do not gain write access automatically.
File uploads through MCP are limited to 8 MiB per call. Saving a draft does
not publish a Brand Release.

v0 stores the connection. This repository contains no credentials, customer
data, business rules, prompts, validators, or implementation logic. All
protected behavior runs on Perture infrastructure and is authorized on every
request.
