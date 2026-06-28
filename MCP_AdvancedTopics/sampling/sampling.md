## Sampling: 
The client makes the LLM calls and return response to the "MCP Server" in order to separate the API call complexity.

- Server creates a prompt
- Client call LLM

# Benefits:
- Reduce Server complexity.
- Client hand the token cost.
- The Server doesnt need API key (More accesible in case of public servers).