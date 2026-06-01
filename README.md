# AI Instagram DM Agent (n8n + ManyChat + OpenAI)

An AI-powered Instagram DM automation workflow built with n8n, ManyChat, and OpenAI.

This workflow automatically receives Instagram messages through ManyChat, processes them with ChatGPT inside n8n, maintains conversation memory, and sends intelligent responses back to Instagram users.

## Features

- Instagram DM automation
- OpenAI-powered conversational responses
- Persistent chat memory
- Custom AI personality/system prompts
- Webhook-based architecture
- No-code/low-code setup
- Easy customization
- ManyChat integration

## Workflow Overview

Instagram DM  
→ ManyChat Webhook  
→ n8n Webhook Trigger  
→ AI Agent + OpenAI  
→ Conversation Memory  
→ AI Response  
→ ManyChat  
→ Instagram User

## Technologies Used

- n8n
- ManyChat
- OpenAI API
- Webhooks
- Conversational AI

## Setup Instructions

### 1. Import Workflow into n8n

- Open n8n
- Import `improved_instagram_ai_agent_workflow.json`

### 2. Configure OpenAI Credentials

Add your OpenAI API key inside the OpenAI node.

### 3. Configure ManyChat

- Create a Custom Action in ManyChat
- Paste the production webhook URL from n8n
- Send:
  - message text
  - session ID/user ID

### 4. Customize AI Personality

Inside the “Set your system prompt for AI” node, modify:
- AI behavior
- tone
- writing style
- niche/persona

## Use Cases

- Influencer auto-replies
- Lead qualification
- Customer support
- AI sales assistant
- Creator engagement automation
- Instagram business automation

## Future Improvements

- Voice note support
- Image understanding
- CRM integration
- Vector memory
- Multi-agent workflows
- Analytics dashboard

## Repository Topics

n8n, openai, instagram-bot, manychat, automation, ai-agent, chatbot, workflow-automation, instagram-automation, llm

## License

MIT
