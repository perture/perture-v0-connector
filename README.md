# Perture for v0 (private connector specification)

v0 currently supports bring-your-own MCP servers and MCP tools exposed by
Vercel Marketplace integrations. It does not provide the same third-party
code-plugin package surface as Codex or Cursor. Because this integration does
not rely on MCP, this repository records the safe future adapter contract
without pretending that an installable v0 plugin already exists.

An eventual native integration must call the explicit Perture gateway
operations from a controlled build-time workflow, use the `v0` client and
audience, request only the needed brand context, and keep generated apps
independent from Perture runtime credentials.

The gateway URL in this repository is a release target. No v0 publication,
Vercel Marketplace registration, connector installation, or Perture app
deployment is included.
