# MCP AI Agent

Welcome to the MCP AI Agent repository! 🚀 This project is a demonstration of how **Model Context Protocol (MCP)** can extend the capabilities of **Large Language Models (LLMs)** by enabling them to interact with real-time data and external tools. In this project, I built an AI agent capable of posting tweets on command using MCP principles.

## 🔍 Overview

The core concept of this project revolves around **MCP**, which allows LLMs to interact with external tools and data in a controlled and secure way. By implementing MCP, I was able to transition the AI from a static knowledge base (which can't access live data) to a dynamic agent that can perform actions like posting tweets.

### Key Features:
- **MCP Integration**: Extend an LLM’s capabilities using real-time data and external tools.
- **Twitter Bot**: The AI can compose and post tweets to Twitter using a custom-built tool.
- **Tool Schema Validation**: Inputs and outputs are strictly validated using `Zod`.
- **Streaming Interface**: Utilized `SSEServerTransport` to establish continuous connections.

---

## 🧪 Project Setup

To set up the MCP AI Agent on your local machine, follow these steps:

### Prerequisites:
- Node.js (v16 or higher)
- TypeScript
- NPM or Yarn (for package management)
- Twitter Developer Account (to access API keys)

### Installation:

1. Clone the repository:

    ```bash
    git clone https://github.com/Atharvadethe/MCP_AI_AGENT.git
    cd MCP_AI_AGENT
    ```

2. Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    ```

3. Set up environment variables:

    Create a `.env` file in the root directory and add your Twitter API credentials



4. Build and run the application:

    ```bash
    npm run build
    npm start
    ```

5. Now your AI agent is ready to post tweets on demand! 🎉

---

## ⚡ Key Concepts

- **Model Context Protocol (MCP)**: MCP is a protocol that allows LLMs to interact with real-time data or external actions through custom tools. It gives LLMs the ability to perform actions (like posting on Twitter) that were previously outside their scope due to data limitations.
  
- **SSEServerTransport**: This is used to establish a streaming connection, allowing the AI agent to continuously interact with external systems in real-time.
  
- **Zod**: A TypeScript-first schema declaration and validation library, used to ensure that inputs and outputs are strictly validated when interacting with the AI's tools.

---

## 🧑‍💻 How It Works

1. **Establishing Connections**: Using `SSEServerTransport`, I set up a continuous data stream for interaction between the LLM and the external system (Twitter, in this case).

2. **Defining Tool Schemas**: I used `Zod` to define and validate the input and output schemas, ensuring that only correct and expected data is passed through to the tool.

3. **Creating the Twitter Posting Tool**: I created a custom tool for posting tweets, which the AI can trigger based on specific commands.

4. **Interaction**: The AI agent can now send tweets using commands, marking a significant leap from static responses to active actions.


---

## 💬 Feedback & Contributions

If you have ideas for improving the project or would like to contribute, feel free to open an issue or submit a pull request!

I’m always open to feedback and would love to hear from you. If you have any questions or suggestions, don't hesitate to reach out!

---

## ✨ License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 📢 Let's Build Together!

If you’re exploring MCP or building similar AI agents, I’d love to connect and exchange ideas. Let’s push the boundaries of what AI can do! 🚀

Feel free to check out the project and drop me a star if you like it! 🌟

#MCP #AI #LLM #MachineLearning #TwitterBot #OpenSource #BuildingInPublic #AIExperimentation
