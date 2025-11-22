# 1. Problem Statement

The goal is to create an **ONCLICK Email Workflow in n8n** that automatically sends an email when triggered (via Manual Trigger or ON CHAT MESSAGE TRIGGER).  
This workflow uses Gmail authentication and an Email node to deliver the message.

---

# 2. Step-by-Step Process

## **Initial Setup**
1. Visit the official n8n website: https://www.n8n.io  
2. Create a new account or sign in if you already have one.  
3. In your personal folder, create a **new empty workflow**.

---

## **Create the ONCLICK Email Workflow**

1. Click **“Add first step…”** and add an **ON CHAT MESSAGE TRIGGER**.  
2. Click the **"+"** button and add a **Manual Trigger**.  
3. Click the **"+"** next to the Manual Trigger and add an **Email Node**.  
4. Select the Email Node and click **Create New Credential**.  
5. Log in with your **Gmail account** to authenticate.  
6. Enter the required fields:
   - Recipient Email ID  
   - Subject  
   - Message  
7. Click **Execute Workflow** to run the workflow.  
8. Check your inbox to confirm the email has been received.  
9. Now your ONCLICK email workflow is ready to use. 👍👍

---

# 3. Implementation Screenshot

Your workflow should look like this:

<img width="1920" height="931" alt="▶️ My workflow - n8n - Google Chrome 21-11-2025 12_31_06" src="https://github.com/user-attachments/assets/b3cc5dd6-ee7a-4603-b2de-405553d04a15" />


---

# 4. Output Screenshot
The mail should have reached your inbox and it should look like this:

<img width="1920" height="992" alt="Manual Trigger - sanjaynewbie2@gmail com - Gmail - Google Chrome 22-11-2025 10_12_39" src="https://github.com/user-attachments/assets/26faa912-6c38-4d05-9091-21ba62d574b2" />


---

# 5. Summary / Learning Outcome

By completing this task, you learned:

- How to create a workflow in n8n.  
- How to use **Manual Trigger** and **Chat Message Trigger**.  
- How to configure and authenticate the **Email Node** using Gmail.  
- How to run and test an automated email workflow.  
- Core concepts of building simple ONCLICK automations in n8n.

This workflow serves as a foundation for building more advanced automation systems.

---
