![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n+ - Secure Workflow Automation for Technical Teams (plus edition)

n8n+ is a workflow automation platform that gives technical teams the flexibility of code with the speed of no-code. With 400+ integrations, native AI capabilities, and a fair-code license, n8n+ lets you build powerful automations while maintaining full control over your data and deployments.

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## Key Capabilities

- **Code When You Need It**: Write JavaScript/Python, add npm packages, or use the visual interface
- **AI-Native Platform**: Build AI agent workflows based on LangChain with your own data and models
- **Full Control**: Self-host with our fair-code license or use our [cloud offering](https://app.n8n.cloud/login)
- **Enterprise-Ready**: Advanced permissions, SSO, and air-gapped deployments
- **Active Community**: 400+ integrations and 900+ ready-to-use [templates](https://n8n.io/workflows)

## Plus Edition Features

- **Advanced Access Control**: Admin roles with fine-grained permissions
- **Global Variables**: Share configurations across workflows
- **Extended History**: Workflow history up to 5 days
- **Enhanced Search**: Advanced execution search capabilities
- **Unlimited Sharing**: Unlimited shared-projects for team collaboration
- **High Performance**: 200+ concurrent executions support
- **Enterprise Authentication**: SSO SAML and LDAP authentication
- **Multi-Environment**: Isolated development, production and other environments
- **External Secrets**: Integration with external secret stores
- **Log Streaming**: Real-time log streaming for monitoring
- **Git Integration**: Version control for your workflows
- **Scalability**: Advanced scaling options for high-demand scenarios
- **Unlimited Data**: Unlimited data retention

## Quick Start

Try n8n+ instantly with [npx](https://docs.n8n.io/hosting/installation/npm/) (requires [Node.js](https://nodejs.org/en/)):

```
npx @n8n-plus/n8n-plus
```

Or deploy with [Docker](https://docs.n8n.io/hosting/installation/docker/):

```
docker volume create n8n_data
docker run -it --rm --name n8n -p 5678:5678 -v n8n_data:/home/node/.n8n ghcr.io/n8n-plus/n8n-plus
```

Access the editor at http://localhost:5678

## Resources

- 📚 [Documentation](https://docs.n8n.io)
- 🔧 [400+ Integrations](https://n8n.io/integrations)
- 💡 [Example Workflows](https://n8n.io/workflows)
- 🤖 [AI & LangChain Guide](https://docs.n8n.io/langchain/)
- 👥 [Community Forum](https://community.n8n.io)
- 📖 [Community Tutorials](https://community.n8n.io/c/tutorials/28)

## Support

Need help? Our community forum is the place to get support and connect with other users:
[community.n8n.io](https://community.n8n.io)
