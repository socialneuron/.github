# Social Neuron

Social Neuron plans, creates, schedules and measures social content for your brand. It is content that learns what works: results from what you publish feed back into what gets made next.

## Use Social Neuron in your assistant

Every option below signs in to your own Social Neuron account.

| Assistant | How to add it | Status |
|---|---|---|
| Grok Build | Plugin source: [plugins/socialneuron](https://github.com/socialneuron/mcp-server/tree/main/plugins/socialneuron). Install from the repository: `grok plugin install socialneuron/mcp-server#plugins/socialneuron --trust` | Available from the repository. Marketplace listing is in review. |
| ChatGPT | Add as a custom connector in Developer mode with the URL `https://mcp.socialneuron.com/mcp`, then sign in in your browser. | Custom connector. |
| Claude | Add as a custom connector with the URL `https://mcp.socialneuron.com/mcp`, then sign in in your browser. | Custom connector. Not in the connector directory yet. |
| Cursor | Use the npm package: add `npx -y @socialneuron/mcp-server` as an MCP server in `.cursor/mcp.json` ([setup](https://github.com/socialneuron/mcp-server#quick-start)). | npm package. |
| Any MCP client, run locally | `npx -y @socialneuron/mcp-server login --device`, then add `npx -y @socialneuron/mcp-server` as a server. | [npm package](https://www.npmjs.com/package/@socialneuron/mcp-server), MIT. |

About the Grok Build plugin: Free MIT plugin; requires a Social Neuron account. Generation uses your plan's credits.

The hosted endpoint and the npm package are two ways to reach the same service. The hosted endpoint uses browser sign-in. The npm package runs on your machine and signs in with a device login or an API key. Both need a plan that includes MCP access; the consent page shows what your plan allows.

## Repositories

| Repository | What it is |
|---|---|
| [mcp-server](https://github.com/socialneuron/mcp-server) | The MCP server, REST API and CLI published as `@socialneuron/mcp-server`, plus the Grok Build plugin under `plugins/socialneuron` |
| [examples](https://github.com/socialneuron/examples) | Prompt-driven workflow templates to copy and run |
| [social-neuron-skill](https://github.com/socialneuron/social-neuron-skill) | A skill package for agent hosts that load skills |

## Licence

The code in these repositories is MIT licensed. Use of the hosted Social Neuron service is covered by the Terms of Service, not by the MIT licence.

## Links

- [socialneuron.com](https://socialneuron.com)
- [For developers](https://socialneuron.com/for-developers)
- [Documentation](https://docs.socialneuron.com/docs/getting-started)
- [Terms of Service](https://socialneuron.com/terms)
- [Privacy Policy](https://socialneuron.com/privacy)
- [Support](https://socialneuron.com/contact)
- [Report a security issue](https://github.com/socialneuron/mcp-server/security/policy)
