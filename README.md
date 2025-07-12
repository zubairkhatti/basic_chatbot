# LangChain Tool-Based Agent (Calculator Bot)

**Overview:**
This is a CLI-based assistant that uses Gemini via LangChain and includes a custom arithmetic calculator tool that can be invoked during conversations.

**Technologies Used:**
- LangChain (tools, messages, React agent)
- Gemini (ChatGoogleGenerativeAI)
- dotenv for API key

**Flow:**
1. Gemini model is initialized.
2. A custom calculator function is registered as a tool.
3. React agent is created using LangGraph's `create_react_agent()`.
4. User inputs text via CLI.
5. Agent either chats or calls the calculator tool.

**Purpose:**
To demonstrate how to integrate tools in an AI assistant using LangChain's React-style agent architecture.