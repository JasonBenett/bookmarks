# AI bookmarks

## MCP Servers

### Atlassian (Jira & Confluence)

* Repo https://github.com/sooperset/mcp-atlassian

Quick Usage example for global availability in Claude Code:
```bash
claude mcp add --scope user --transport stdio mcp-atlassian --env CONFLUENCE_URL={URL} --env CONFLUENCE_PERSONAL_TOKEN={TOKEN} --env JIRA_URL={URL} --env JIRA_PERSONAL_TOKEN={TOKEN} -- docker run -rm -i -e CONFLUENCE_URL -e CONFLUENCE_PERSONAL_TOKEN -e JIRA_URL -e JIRA_PERSONAL_TOKEN -e ghcr.io/sooperset/mcp-atlassian:latest
``` 
