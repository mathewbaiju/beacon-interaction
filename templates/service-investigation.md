# Service Investigation Template

## Quick Investigation Command
```
Investigate service: {SERVICE_NAME}
```

## Detailed Investigation Steps

### 1. Basic Service Information
- Service name and identifier
- Owner/team responsible
- Service type and lifecycle stage
- Primary contact information

### 2. Deployment Information
- Deployed regions
- Environment status (dev, staging, prod)
- Deployment frequency
- Latest deployment timestamp

### 3. Build Status
- Latest successful build
- Build history (last 10 builds)
- Changeset information
- Build duration trends

### 4. Dependencies
- Upstream dependencies (services this depends on)
- Downstream dependencies (services that depend on this)
- API contracts and versions
- Database dependencies

### 5. Health & Monitoring
- Current health status
- Recent incidents or alerts
- Performance metrics
- SLA/SLO compliance

### 6. Stakeholder Information
- Engineering Manager
- Product Manager/Owner
- Support team contacts
- Division/organization structure

## Expected Beacon Navigation Flow
1. Start at catalog: https://beacon.autodesk.com/catalog
2. Search for service name
3. Navigate to service detail page
4. Collect data from all tabs:
   - Overview
   - Build & Deploy
   - Dependencies
   - API
   - Monitoring/Health

## Output Format
Provide structured summary with:
- Executive summary
- Key contacts
- Current status
- Action items or concerns
