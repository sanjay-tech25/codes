# 1. Problem Statement

The goal is to create a workflow in **n8n** that triggers whenever a chat message is received, processes the message using an **AI Agent**, and uses the **Google Gemini Chat Model** as the AI engine.  
This setup enables automated AI-powered responses inside n8n chat interactions.

---

# 2. Step-by-Step Process

## **Initial Setup**
1. Visit the n8n official website: https://www.n8n.io  
2. Create an account or log in if you already have one.  
3. Open your personal workspace and create a **new workflow**.

---

## **Creating the AI Chat Workflow**

1. Click **“Add first step…”** and add a  
   **➤ When Chat Message Received Trigger**  
   This node activates whenever a user sends a message in the n8n chat window.

2. Click the **“+”** button and add an **AI Agent** node.  
   This will allow you to configure how the AI responds to incoming messages.

3. Add a **Google Gemini Chat Model** node.  
   - Connect it to the **Chat Model** input of the AI Agent.  
   - Authenticate using your Google API or service credentials.  
   - Choose your preferred Gemini model (e.g., Gemini Pro, Gemini Flash).

4. (Optional) Add memory and tool nodes to enhance the AI Agent’s capabilities:  
   - Memory → to store conversation history  
   - Tools → to give the agent special functions

5. Save the workflow.  
6. Click **Open Chat** and send a test message to verify AI responses.

---

# 3. Implementation Screenshot

Your workflow should look like this:

<img width="1920" height="943" alt="▶️ My workflow 2 - n8n - Google Chrome 21-11-2025 12_11_40" src="https://github.com/user-attachments/assets/f17793bc-7836-4f11-af2b-0548909bef4f" />

---

# 4. Output Screenshot

A mail should have reached the recipient mail like this:

<img width="1920" height="1032" alt="Here&#39;s the information - sanjaynewbie2@gmail com - Gmail - Google Chrome 22-11-2025 11_11_06" src="https://github.com/user-attachments/assets/97d6c598-82e3-4595-acb6-37af2c2e77af" />

---

# 5. Summary / Learning Outcome

By completing this setup, you learned:

- How to use the **When Chat Message Received** trigger in n8n  
- How to configure an **AI Agent** node  
- How to connect the **Google Gemini Chat Model** to the AI Agent  
- How to build an AI-powered chat system inside n8n  
- The basics of integrating LLMs into workflow automations  

This forms a strong foundation for building advanced conversational automations, customer support bots, or AI-driven assistants using n8n.

---
