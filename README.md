# Beacon Interaction

A dedicated toolkit for automating Beacon catalog interactions and service investigations.

![Happy TPM](https://github.com/user-attachments/assets/0f11d60f-e056-4dec-a75b-0be04ee6cf88)


## Purpose

This repository contains tools and automation for:
- Service investigation workflows
- Beacon catalog navigation
- Build status monitoring
- Dependency analysis
- Stakeholder mapping

## Features

- **MCP Server**: Custom Model Context Protocol server for Beacon interactions
- **Service Investigation**: Automated workflows for comprehensive service analysis
- **Build Monitoring**: Tools for tracking build status and changes
- **Templates**: Reusable prompt templates for common investigations

## Quick Start

### Service Investigation
```
Investigate service: {SERVICE_NAME}
```

### Build Analysis
```
Analyze latest build for {SERVICE_NAME}
```

### Health Check
```
Check health status of {SERVICE_NAME}
```

## Common Beacon URLs

- [Main Catalog](https://beacon.autodesk.com/catalog?filters%5Buser%5D=all&filters%5Bkind%5D=component&limit=20)
- Service Template: `https://beacon.autodesk.com/catalog/default/component/{service-name}`

## Setup

1. Configure MCP servers in Claude Desktop
2. Install required dependencies
3. Set up environment variables for Beacon access

## Usage

This toolkit is designed to work with Claude Desktop and MCP servers for seamless service investigation workflows.
