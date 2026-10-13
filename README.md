# DSH client identity document (CIMD)

This public repository exists only to serve `client-metadata.json` over HTTPS
with the `application/json` content type, as required by the Client ID Metadata
Document flow (SEP-991) that the ElevenLabs hosted MCP authorization server
uses instead of dynamic client registration.

The document is referenced as the `client_id` by the DeepSeek Harness
ElevenLabs MCP connector and by the local `mcp-remote` bridge.

Served through jsDelivr: https://cdn.jsdelivr.net/gh/EnriqueZGK/dsh-elevenlabs-mcp-client@main/client-metadata.json
