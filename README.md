# n8n-workflows
n8n workflows for various projects.


| Project      | Description |
| ------------ | ----------- |
| Telegram_bot | The backend for a Telegram bot. Users can send the bot messages and receive replies from an LLM. <br/> Features: Conditional tooling: the Agent has an HTTP Request tool to Home Assistant's RESTful API to GET sensor data. The data is interpreted by the LLM to determine a yes/no response back to the Telegram user. <br/> Parameter tooling: The Agent must decide which tool to use based on the prompt and which parameter to pass to the GET request. |
