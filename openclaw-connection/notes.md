\# Zapier MCP — Connection Notes

\- \*\*Server:\*\* \`[https://mcp.zapier.com/api/v1/connect\`](https://mcp.zapier.com/api/v1/connect) via mcporter  
\- \*\*OAuth callback port:\*\* Fixed to \`44411\` via \`oauthRedirectUrl\` in \`config/mcporter.json\` so SSH forwarding works: \`ssh \-L 44411:[127.0.0.1:44411](http://127.0.0.1:44411/) \<host\>\`  
\- \*\*Apps connected:\*\* Google Calendar \+ Google Docs (both edenjoybot@gmail.com), auto-provisioned  
\- \*\*Tools available:\*\* 17 Zapier MCP tools — discover, enable, read/write actions across 9,000+ apps  
\- \*\*Onboarding status:\*\* Partially done — auth is live, but the onboarding rundown was paused before saving a reusable skill. Needs app additions (e.g. Gmail, Slack) for a meaningful multi-source demo.