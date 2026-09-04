# Frida brand

The Frida app icon, hosted publicly so that OAuth consent screens can load it.

Frida registers itself with each MCP server it connects to using RFC 7591
dynamic client registration, and `logo_uri` in that registration has to be an
absolute `https:` URL that the service's own consent page can fetch. A data URI
is rejected, and the app repository is private, so the icon lives here.

`frida-icon.png` — 512x512, transparent corners. This is the shipping app icon,
not a variant of it. Changing it changes what people see when they are deciding
whether to give Frida access to their account, so change it only when the app
icon itself changes.

Referenced from `MCPAuth.register`.
