# HexStrike-MCP-Setup
Practical lab guide documenting the installation, configuration, and server health checks of the HexStrike Model Context Protocol (MCP) server integrated with Claude Desktop in a Kali Linux environment.
# HexStrike MCP Server Setup and Configuration

A comprehensive practical lab demonstrating the deployment, configuration, and health monitoring of the HexStrike Model Context Protocol (MCP) server integrated with Claude Desktop within a Kali Linux environment.

## Lab Overview
* **Objective:** Set up and configure the HexStrike AI offensive intelligence core and MCP tools server to establish an integrated local testing environment.
* **Environment:** Kali Linux virtual machine operating via Oracle VirtualBox, utilizing Python, virtual environments (`hexstrike-env`), and Claude Desktop integration.
* **Methodology:**
  * Installed Claude Code and configured Claude Desktop on the local Kali Linux host.
  * Cloned and set up the HexStrike repository, resolving dependency installations and environment requirements.
  * Started the HexStrike AI tools API server locally on port 8888.
  * Configured the Claude Desktop Model Context Protocol configuration file (`claude_desktop_config.json`) to communicate with the local HexStrike server.
  * Executed comprehensive health checks and reviewed binary coverage statistics across security tool categories (including essential, network, password, forensics, and web security tools).
* **Result:** Successfully established a functioning local HexStrike MCP server connection with active server health monitoring, resource usage tracking, and tool wrapper status validation.

* [HexStrike-MCP-Setup.pdf](https://github.com/user-attachments/files/34986371/HexStrike-MCP-Setup.pdf)
