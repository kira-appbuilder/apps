# LocalAgent Hub

*A beautiful dashboard for managing and monitoring locally-running AI agents*

## Overview

LocalAgent Hub is a minimalist mission control center for self-hosted AI infrastructure. Designed for indie developers and privacy-conscious users, it provides calm, aesthetic monitoring of local AI agents like Qwen3.6-Plus, AMD Lemonade LLM servers, and other AI tools.

## Features

- **Beautiful Monitoring**: Real-time resource usage (CPU, Memory, GPU) with elegant progress bars
- **Agent Health Checks**: Live status indicators with gentle notifications
- **Activity Logging**: Timestamped activity feed with automatic cleanup
- **Calm Design**: Minimalist dark interface that focuses on clarity over complexity
- **Bilingual Support**: Toggle between English and Japanese (日本語)
- **Self-Contained**: Single HTML file - no dependencies or servers required

## Usage

1. Download or save the `index.html` file
2. Open it in any modern web browser
3. The dashboard will display with mock AI agents for demonstration
4. Use the language toggle (top-right) to switch between English/Japanese
5. Interact with buttons to see activity logging in action

## Interface Elements

- **Agent Cards**: Show status, response times, and resource usage for each AI agent
- **Resource Bars**: Real-time CPU, RAM, and GPU usage with gradient indicators
- **Activity Log**: Recent events and system messages with timestamps
- **Action Buttons**: Add agents, run health checks, and access settings

## Design Philosophy

*"静かな監視。信頼できる知能。"* (Calm monitoring. Trustworthy intelligence.)

The interface prioritizes:
- Functional beauty over technical complexity
- Gentle notifications instead of alerts
- Privacy-first local infrastructure
- Approachable AI monitoring for developers

## Customization

The dashboard uses a modular CSS design system that can be easily customized:
- Modify accent colors (currently cyan/sage theme)
- Adjust resource update intervals in JavaScript
- Add new agent types or monitoring metrics
- Integrate with real AI agent APIs

## Browser Compatibility

Works in all modern browsers with CSS Grid and Fetch API support (Chrome 57+, Firefox 52+, Safari 10.1+, Edge 16+).
