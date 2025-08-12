# Useful Prompts for Beacon Interaction & Technical Program Management

## Core Service Investigation Workflows

### Standard Service Investigation
```
Investigate service: {SERVICE_NAME}
```
**What it does**: Comprehensive service analysis using Beacon catalog including owner, regions, build status, dependencies, and stakeholder information.

### Quick Health Check
```
Check health status of {SERVICE_NAME}
```
**What it does**: Rapid assessment of service health, build status, and deployment status across regions.

### Build Analysis
```
Analyze latest build for {SERVICE_NAME}
```
**What it does**: Deep dive into latest successful build, changesets, and impact analysis.

### Dependency Mapping
```
Map dependencies for {SERVICE_NAME}
```
**What it does**: Identify and visualize upstream/downstream dependencies, API contracts, and integration points.

## MCP Server Management

### Check MCP Status
```
List all active MCP servers and their current status
```
**What it does**: Shows all configured MCP servers with status indicators (✅/❌).

### Restart MCP Services
```
Restart all MCP servers
```
**What it does**: Refreshes MCP connections for better performance.

## Beacon Navigation Shortcuts

### Direct Beacon Access
```
Navigate to Beacon catalog and search for {SERVICE_NAME}
```
**What it does**: Opens Beacon catalog and performs service search using Playwright MCP.

### Service Deep Dive
```
Open {SERVICE_NAME} in Beacon and collect all available information
```
**What it does**: Comprehensive data collection from all Beacon tabs (Overview, Build & Deploy, Dependencies, API, Monitoring).

## Advanced Workflows

### Stakeholder Analysis
```
For {SERVICE_NAME}, identify all stakeholders including:
1. Engineering Manager
2. Product Manager/Owner
3. Support team contacts
4. Division structure
```

### Build Trend Analysis
```
Analyze build trends for {SERVICE_NAME} over the last 30 days
```

### Incident Investigation
```
Investigate recent incidents for {SERVICE_NAME} and correlate with deployments
```

### Regional Deployment Status
```
Check deployment status of {SERVICE_NAME} across all regions
```

## Quick Commands

### One-Line Investigations
- `health {SERVICE}` → Quick health check
- `build {SERVICE}` → Latest build status
- `deps {SERVICE}` → Dependency overview
- `owner {SERVICE}` → Service ownership info
- `regions {SERVICE}` → Deployment regions

### Batch Operations
```
Investigate multiple services: {SERVICE1}, {SERVICE2}, {SERVICE3}
```

## Repository Management

### Force Sync Repository
```
Force-sync stakeholder-mapping source from remote
```
**What it does**: Performs `git fetch origin && git reset --hard origin/main && git clean -fd` to completely sync with remote.

### Create New Repository
```
Create a new Git repo with the name "{REPO_NAME}"
```

### Move Repository
```
Move this repo out of {CURRENT_FOLDER} to {NEW_LOCATION}
```

## Automation Templates

### Daily Service Health Report
```
Generate daily health report for services: {SERVICE_LIST}
Include:
- Build status
- Deployment status
- Recent incidents
- Dependency alerts
```

### Weekly Stakeholder Update
```
Create weekly stakeholder update for {PROGRAM_NAME}:
- Service health summary
- Recent deployments
- Upcoming changes
- Risk assessments
```

### Quarterly Service Review
```
Perform quarterly review for {SERVICE_NAME}:
- Performance trends
- Incident analysis
- Dependency evolution
- Stakeholder feedback
```

## Integration Prompts

### Miro Board Analysis
```
Analyze this Miro board: {MIRO_URL}
Extract stakeholder mapping and roadmap information
```

### Service Documentation
```
Generate comprehensive documentation for {SERVICE_NAME} based on Beacon data
```

### Risk Assessment
```
Assess deployment risks for {SERVICE_NAME} considering:
- Dependency health
- Recent changes
- Historical incidents
- Regional variations
```

## Troubleshooting

### MCP Connection Issues
```
Debug MCP server connectivity issues and provide resolution steps
```

### Beacon Access Problems
```
Troubleshoot Beacon catalog access and navigation issues
```

### Service Investigation Failures
```
When service investigation fails, try alternative data sources and manual verification
```

## Useful Beacon URLs

- **Main Catalog**: https://beacon.autodesk.com/catalog?filters%5Buser%5D=all&filters%5Bkind%5D=component&limit=20
- **Service Template**: https://beacon.autodesk.com/catalog/default/component/{service-name}
- **Search Template**: https://beacon.autodesk.com/catalog?q={search-term}

## Best Practices

1. **Always start with MCP status check** before complex workflows
2. **Use specific service names** rather than partial matches
3. **Combine multiple data sources** for comprehensive analysis
4. **Document findings** for future reference
5. **Verify critical information** through multiple channels
6. **Keep stakeholder information updated** in service records

## Custom Workflows

### Emergency Response
```
Emergency investigation for {SERVICE_NAME}:
1. Current health status
2. Recent deployments
3. Active incidents
4. Immediate contacts
5. Rollback options
```

### Change Impact Analysis
```
Analyze impact of proposed changes to {SERVICE_NAME}:
- Dependent services
- Stakeholder notifications
- Rollback planning
- Risk mitigation
```

### Performance Investigation
```
Investigate performance issues for {SERVICE_NAME}:
- Build trends
- Deployment patterns
- Dependency performance
- Regional variations
```

---

## Usage Notes

- Replace `{SERVICE_NAME}`, `{REPO_NAME}`, etc. with actual values
- Most prompts work with Playwright MCP for Beacon navigation
- Miro prompts require Miro MCP server configuration
- Always verify critical information through multiple sources
- Keep this file updated with new workflows and learnings
