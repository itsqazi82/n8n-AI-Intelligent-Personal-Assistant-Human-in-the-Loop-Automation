# 🤖 Haseeb AI — Personal AI Assistant

Haseeb AI is a **personal AI assistant built with n8n and OpenAI** that understands natural-language commands and connects them with everyday tools such as Gmail, Google Calendar, Web Search, Wikipedia, and Calculator.

## 🎯 Why I Built It

Managing emails, calendar events, searches, and repetitive tasks manually can be time-consuming. I wanted to build an assistant that can understand what I want in normal language and handle the workflow for me.

The main challenge was not just making an AI that can respond, but building one that can **safely interact with real-world services while keeping the user in control**.

## ⚙️ How It Works

```text
User Request
     ↓
Web Form
     ↓
AI Request Processor
     ↓
Understand & Prepare Action
     ↓
Human Approval
     ↓
IF Approved?
   ↙       ↘
 YES       NO
  ↓         ↓
Execute   Cancel / Re-process
```

For example:

> "Send an email to my client telling him that the project is almost complete."

The AI understands the request, prepares the recipient, subject, and email content, and sends it for approval before the actual email is sent.

## 🔐 Key Feature

The most important part of this project is the **Human-in-the-Loop approval system**.

AI can prepare an action, but it should not automatically perform important external actions without user approval.

This creates a safer workflow:

**AI prepares → Human approves → Automation executes**

## 🛠️ Tools Used

* n8n
* OpenAI
* Gmail
* Google Calendar
* Brave Search
* Wikipedia
* Calculator
* Simple Memory
* n8n Form

## 💡 Problem Solved

This project turns multiple manual tasks into a **single natural-language interface**, while adding an approval layer for actions that can have real-world consequences.

It is also an exploration of how **AI Agents, tool calling, memory, automation, and human approval** can work together in a practical system.

<img width="1604" height="489" alt="image" src="https://github.com/user-attachments/assets/b04fd76b-5498-45a1-bbb8-0fd910dfc40f" />
<img width="1671" height="718" alt="image" src="https://github.com/user-attachments/assets/8ae19c37-effd-4504-bfaa-8fd8b33fe4ce" />
