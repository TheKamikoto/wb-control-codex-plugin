# WB Control for Codex

Connect Codex to saved Wildberries sales, stocks and cost analytics. The assistant
offers recommendations; managers apply changes in their usual interfaces.

## Install

Add this Git repository as a Codex plugin marketplace, then install **WB Control**.
The plugin already contains the server URL and public OAuth client settings.
Do not enter shell commands, API keys, client secrets or callback settings in the
MCP server form. On a device with this marketplace already configured, use the
plugin installation flow in Codex.

Sign into [WB Control](https://wb-control.ru), obtain MCP permission from your
workspace administrator, and confirm your cabinet during OAuth. Installation does
not grant access by itself. Different managers receive independent connections;
connections can be revoked in WB Control Settings → MCP.

This is a **closed pilot**. Cabinet access is allowlisted on the server. A public
plugin repository does not make private shop data public or remove access checks.
Financial coverage limitations remain visible; confirmed net profit is not implied.

## Distribution

This repository contains only plugin manifests and public connection metadata.
It is a Git marketplace, not a listing in the official OpenAI plugin directory.
New devices must first add the marketplace. The website cannot silently configure
an external application or approve personal cabinet access for a user.

The plugin has no hooks, install scripts, shared bearer credentials or embedded
secrets. Its existing public client uses a loopback callback managed by Codex.
It does not alter the user's tool approval settings or run advertising automation.
