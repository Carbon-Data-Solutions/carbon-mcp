# Carbon MCP connector

**Listing name:** Carbon  
**Product:** carbon.talent  
**Connector URL:** https://mcp.carbondatasolutions.com/mcp  
**Homepage:** https://www.carbondatasolutions.com/hire  
**Support:** talent@carbondatasolutions.com  
**Privacy:** https://www.carbondatasolutions.com/privacy

## One-line

Hire data professionals from ChatGPT, Claude, or any MCP host. Post a role free.

## What it does

Hiring a data person shouldn't feel like a gamble. You need someone who can do the work, and you need a clear path from role draft to offer without leaving the assistant you already use.

Carbon connects carbon.talent to your AI assistant. Search the talent catalog, draft and post a role, review applicants, and move people through Applied, Screened, Interview, and Offer. Writes ask for your confirmation first. Post a role free. The once-off fee is waived on your first hire. Already have a candidate? Skills tests start from about $110 (about €95).

## Features

- Search the talent catalog by skills, experience, and location (first name plus last initial)
- Open a talent profile without contact details, CV, rates, or scores
- Create a role draft and post it when you are ready (confirm on every write)
- List your roles and open any role for detail
- List applicants for a role and read an applicant summary (no contact details, CV, rates, or scores)
- Move an applicant to Applied, Screened, Interview, or Offer (never Hired via the connector)
- Sign in with OAuth; company-scoped data only; disconnect any time from your Carbon account or the host

## Tools

| Tool | Access | Short description |
|------|--------|-------------------|
| `whoami` | read | Show my account |
| `list_roles` | read | List my roles |
| `get_role` | read | Get a role |
| `create_role_draft` | write, confirm | Create a role draft |
| `post_role` | write, confirm | Post a role |
| `list_applicants` | read | List applicants for a role |
| `get_applicant_summary` | read | Get an applicant summary (no contact details, CV, rates or scores) |
| `move_applicant_stage` | write, confirm | Move an applicant to a stage (Applied / Screened / Interview / Offer only; never Hired) |
| `search_talent` | read | Search the talent catalog (first name plus last initial) |
| `get_talent_profile` | read | Get a talent profile |

## Connect (any MCP host)

Use Streamable HTTP at:

`https://mcp.carbondatasolutions.com/mcp`

Sign in with OAuth to a carbon.talent company account.

### Cursor / Open Plugins `.mcp.json`

```json
{
  "mcpServers": {
    "carbon": {
      "type": "streamable-http",
      "url": "https://mcp.carbondatasolutions.com/mcp"
    }
  }
}
```

## Offers

- Post a role free
- The once-off fee is waived on your first hire
- Skills tests from about $110 (about €95)

## Honest claim rules

Do not say Carbon is live inside ChatGPT, Claude, Copilot, Gemini, or Cursor directories until that directory lists it. Safe today: the MCP endpoint is live and hosts can connect by URL where custom connectors are allowed.
