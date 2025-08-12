# Favorite Cursor Prompts for Technical Program Management

## MCP Server Management
```
List all active MCP servers and their current status
```

## Service Investigation
```
I need to investigate the {SERVICE_NAME} service. Please:
1. Navigate to Beacon catalog
2. Search for {SERVICE_NAME}
3. Retrieve all service details including regions, contacts, and build status
4. Show the latest successful build and its changesets
```

## Build Analysis
```
For {SERVICE_NAME}, can you:
1. Check the latest successful build
2. Fetch the changesets included
3. Summarize the key changes and their impact
```

## Dependency Mapping
```
For {SERVICE_NAME}, please:
1. Navigate to the Dependencies tab in Beacon
2. List all upstream and downstream dependencies
3. Create a dependency diagram if possible
```

## Health Check
```
Check the health of {SERVICE_NAME}:
1. Verify build status
2. Check deployment status across all regions
3. Review any recent incidents or alerts
```

## Stakeholder Analysis
```
For {SERVICE_NAME}, identify:
1. Engineering Manager
2. Product Manager
3. Product Owner
4. Support team contacts
5. Division and organizational structure
```

## Quick Beacon Navigation
```
Use Playwright MCP to open Beacon catalog and navigate to {SERVICE_NAME}
```

## MCP Workflow Templates

### Standard Service Investigation Workflow
1. Check MCP status: `list all the MCPs active`
2. Open Beacon: Navigate to catalog
3. Search service: Search for specific service
4. Get details: Retrieve comprehensive information
5. Check builds: Latest successful build analysis
6. Get changesets: Detailed change information

### Quick Service Health Check
1. `is there build status available for {SERVICE}`
2. `which is the latest build that's successful`
3. `which regions is {SERVICE} deployed`

## Useful Beacon URLs for Copy-Paste
- Main Catalog: https://beacon.autodesk.com/catalog?filters%5Buser%5D=all&filters%5Bkind%5D=component&limit=20
- WIPDM Service: https://beacon.autodesk.com/catalog/default/component/wipdm-service

## Repository Management
```
Force-sync stakeholder-mapping source from remote
```

```
Create a new Git repo with the name "{REPO_NAME}"
```

```
Move this repo out of {CURRENT_FOLDER} to {NEW_LOCATION}
```

## Quick Commands
- `investigate {SERVICE}` → Full service investigation
- `health {SERVICE}` → Health and deployment status
- `build {SERVICE}` → Latest build status
- `deps {SERVICE}` → Dependency analysis
- `owner {SERVICE}` → Service ownership info
- `regions {SERVICE}` → Deployment regions
