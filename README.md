# DocStar MCP Server

Connect DocStar with Cursor using the Model Context Protocol (MCP).

## Overview

DocStar MCP aims to make DocStar functionality accessible through MCP-compatible AI clients, including Cursor.

## Features

- Connect Cursor to DocStar through MCP.
- Authenticate securely using OAuth.
- Access supported DocStar operations through MCP tools.

*Note: Features depend on the tools implemented by the MCP server.*

## Requirements

- Cursor with MCP support.
- A DocStar account with the required permissions.
- A deployed MCP server endpoint, or a locally configured MCP server.

## Authentication

DocStar uses OAuth authentication. Users should authenticate through the supported sign-in flow.

Never commit access tokens, refresh tokens, client secrets, or other sensitive credentials to this repository.

## Setup

Installation instructions and the MCP configuration will be added once the server implementation and endpoint are available.

## Development Status

This project is under development. A working MCP server and verified installation instructions are required before general use.

## Support

For issues or feature requests, open an issue in this repository.
