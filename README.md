# n8n MCP Client — AI Agent Integration

## Overview

An AI-powered workflow built using n8n that integrates an AI Agent with Model Context Protocol (MCP) clients, enabling interactions with external tools and services.

The workflow uses OpenAI's GPT-5 mini model, GitHub MCP integration, a custom MCP endpoint and conversational memory to explore extensible AI agent architectures.

## Project Objectives

- Explore MCP-based tool integration.
- Build an AI Agent workflow using n8n.
- Connect AI agents with external tools and services.
- Maintain conversational context through memory.
- Demonstrate a modular approach to AI workflow orchestration.

## Technology Stack

- **Workflow Automation:** n8n
- **AI Model:** OpenAI GPT-5 mini
- **Agent Framework:** n8n LangChain AI Agent
- **Tool Integration:** Model Context Protocol (MCP)
- **External Integration:** GitHub MCP
- **Memory:** Simple Memory with a context window of 10 messages

## Workflow Architecture

1. **Chat Trigger:** Receives incoming user messages.
2. **AI Agent:** Processes user input and coordinates tool interactions.
3. **OpenAI Chat Model:** Provides language-model capabilities.
4. **MCP Clients:** Connect the agent to GitHub and a custom MCP server.
5. **Conversational Memory:** Maintains recent conversation context.

## Key Learnings

- AI agent orchestration and workflow design.
- MCP client configuration and external tool integration.
- Modular AI workflow architecture.
- Conversational memory and contextual interactions.
- Practical applications of agentic AI systems.

## Security Note

This repository contains a sanitized workflow export for educational and portfolio purposes. Authentication credentials and private endpoint identifiers should be configured separately when deploying the workflow.

## Project Status

Workflow configuration and architecture demonstration.

This repository does not claim production deployment, validated tool execution or measured business outcomes.

## Author
DHARODIA VIVEK JIGNESH

Vivek Dharodia

[LinkedIn](https://www.linkedin.com/in/dharodia-vivek-jignesh-9a2b92346)
