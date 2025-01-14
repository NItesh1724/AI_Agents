### Financial Agent

This system is a demonstration of Agentic AI, where multiple specialized agents collaborate to solve a complex task. It focuses on:

1. Web Searches: Using DuckDuckGo for real-time information.
2. Financial Analysis: Using YFinanceTools to process stock data.
3. Orchestration: Coordinating agents for a seamless, accurate, and user-friendly output.

##  Use Cases
Stock Market Analysis: For investors and analysts seeking insights into companies (e.g., Nvidia).
Research Assistance: Combines financial data with real-time news for up-to-date insights.
AI-Assisted Tools: Can be extended for broader applications like portfolio management or market predictions.

 ## 1. Web Search Agent
 
# Objective: This agent is designed to perform web searches and provide relevant information.

name and role: Specify the agent's purpose (web searching).
Model: Uses the Groq language model for understanding instructions and generating responses.
Tools: Integrates DuckDuckGo for conducting web searches.
Instructions: Ensures the agent always includes the sources of its information in its output.

## 2. Financial Agent
# Objective: This agent specializes in financial data analysis.

Tools: The YFinanceTools module is configured to:
Retrieve stock prices.
Summarize analyst recommendations.
Fetch stock fundamentals (e.g., P/E ratios, market cap).
Provide the latest company news.

## 3. Multi-Agent System

Objective: Combines the capabilities of web_search_agent and finance_agent into one multi-agent assistant.

Teamwork: Uses the team parameter to orchestrate multiple agents, allowing them to work together:
The web search agent finds relevant, up-to-date information from the internet.
The finance agent processes and analyzes financial data.

