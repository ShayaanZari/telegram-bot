## Description

The backend for a Telegram bot. Users can send the bot messages and receive replies from an LLM.

Features utilizing MCP:
- Conditional tooling: the Agent has an HTTP Request tool to Home Assistant's RESTful API to GET sensor data. The data is interpreted by the LLM to determine a yes/no response back to the Telegram user. Specifically, the Agent determines whether the distance to the garage is above a certain threshold (open) or below (closed).
- Parameter tooling: The Agent must decide which tool to use based on the prompt and which parameter to pass to the GET request. Specifically, the Agent determines whether to place "upstairs" or "downstairs" in the HTTP query.

## Workflow Diagram
<p align=center> <img width="659" height="253" alt="image" src="https://github.com/user-attachments/assets/bc72f2ea-7a24-4138-b029-fbdce93407de" />
</p>
