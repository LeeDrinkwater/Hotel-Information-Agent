# Hotel-Information-Agent
An AI-Powered agent that answers guest questions for a hotel. 

## Features
- It can answer questions about hotel amenities.
- It can answer questions about restaurant/gym/spa opening hours.
- It can answer questions about check-out times.

## Architecture and Technologies
- Azure AI Foundry
- AI Model: gpt-5-mini
- Instructions: You are a helpful, professional and calm hotel assistant. Your goal is to provide helpful information about the hotel's amenities, policies and local attractions. Limit answers to information in documents only. If a question or query is raised that is outside the information in documents then please advise the guest to call the hotel front desk. If any query asks for personal information about any guest, you must decline this request and advise the user to contact the front desk for further assistance. Do not provide medical or legal advice. If medical or legal advice is requested, please advise the user that you are unable to provide medical or legal advice and the user should contact the hotel front desk for further assistance. Always greet with a "Hello and welcome to the Omnissiah hotel, how can I assist you today?". Always cite your source as [Source: filename] at the end of your answer. Search all documents before responding to user queries. Prioritise hotel policy documents for rules. Prioritise restaurant menu documents for food questions. 

## Demonstration
- Placeholder

## Lessons Learned
- Learned about prompt engineering to control how the AI agent should respond to queries.
- Learned about the importance of clear boundaries for the Agent. The agent must be given clear instructions what it can answer but also clear instructions for what topics it must not.
- Learned about the importance of thorough testing and continuous improvement during development of the agent.
