# LLM-Agent
Browser-Based Multi-Tool Reasoning
Modern LLM-powered agents aren’t limited to text—they can combine LLM output with external tools like web search, pipelined APIs, and even live code execution!
**Supported Tool Calls**
Google Search API: Return snippet results for user queries.
AI Pipe API: Use the aipipe proxy for flexible dataflows.
JavaScript Code Execution: Securely run and display results of user- or agent-provided JS code within the browser.
**UI/Code Requirements**
Model Picker: Use bootstrap-llm-provider so users choose the LLM provider/model.
LLM-Agent API: Use OpenAI-style tool/function calls so the LLM can ask for tool actions and receive their results.
Alert/Error UI: Show errors gracefully with bootstrap-alert.
Code Simplicity: Keep all JavaScript and HTML as simple and small as possible—maximal hackability is the goal!
Implementation Reference: Use apiagent as a starting design, but trim non-essential code.
