# handsup-mcp

Model Context Protocol (MCP) server for handsup functionality.

## Overview

This project implements an MCP server that provides handsup-related capabilities for AI assistants and other MCP clients.

## Configuration

The project includes `mcp.json` configuration file that defines the MCP server settings:

### Production Environment
- **Server Name**: `handsup-mcp-server`
- **Type**: stdio
- **Command**: `node dist/index.js`
- **Environment**: production

### Development Environment
- **Server Name**: `handsup-mcp-dev`
- **Type**: stdio  
- **Command**: `npx tsx src/index.ts`
- **Environment**: development

## Setup

1. Clone the repository
2. Install dependencies: `npm install`
3. Build the project: `npm run build`
4. Configure your MCP client to use the settings from `mcp.json`

## Development

For development, use the `handsup-mcp-dev` configuration which runs TypeScript files directly using tsx.

## Usage

Add the server configuration from `mcp.json` to your MCP client's configuration file to enable the handsup-mcp server functionality.

## Requirements

- Node.js
- npm or yarn
- TypeScript (for development)