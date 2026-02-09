# MegaOS MCP Plugin

Claude Code plugin providing 49 MCP tools for Moltbot to administer Russell's operational apps via Supabase.

## Tools (49)

### WorkOS (12 tools)
Deliverables CRUD, inbox management, market signals, time windows, settings.

### LifeOS (26 tools)
Family profiles, meal planning + shopping list, music feed + feedback, adventure route + bookings + costs, activities, accommodation, settings.

### Jeeves (11 tools)
Task CRUD, AI suggestions with scoring, suggestion-to-task conversion, settings.

## Setup

Requires `SUPABASE_SERVICE_ROLE_KEY` environment variable. Set it in your Claude Code env config:

```json
{
  "env": {
    "SUPABASE_SERVICE_ROLE_KEY": "your-service-role-key"
  }
}
```

## Distribution

Distributed via the CTL Claude Code plugin marketplace.
