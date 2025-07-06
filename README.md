# 🤖 AI Sales Bot Automation with n8n

This is a portfolio project demonstrating an automated AI sales bot built using **n8n**, inspired by the tutorial from [Liyars | n8n | AI automation](https://www.youtube.com/watch?v=W9XMiKa1fe4&ab_channel=Liyars%7Cn8n%7CAIautomation).

---

## 📌 Project Overview

The AI sales bot automates customer interactions in **Telegram**, guiding clients through the sales process and helping close deals.  
The solution is fully implemented using **n8n** with integration of **GPT models** for intelligent conversation handling.

---

## ⚙️ Technical Details

- **Platform**: n8n (self-hosted or cloud)  
- **AI Model**: OpenAI GPT (via official integration)  
- **Workflow Includes**:
  - Telegram Trigger node  
  - AI Agent (OpenAI GPT)  
  - Google Sheets (for storing lead data)  
  - Conditional logic using Switch nodes  

- **Inspired by**:  
  [Liyars’ YouTube Tutorial](https://www.youtube.com/watch?v=W9XMiKa1fe4)

---

## 🚀 Setup Instructions

1. **Clone this repository**:

   ```bash
   git clone <your-repo-url>
   ```

2. **Import the workflow**:
   - Open your n8n instance  
   - Import the `workflow.json` file into the editor

3. **Configure Credentials**:
   - Set up your **Telegram Bot Token**
   - Add your **OpenAI API Key**
   - Connect to **Google Sheets** and replace document IDs with your own

4. **Test**:
   - Start the workflow
   - Open Telegram and interact with the bot

---

## 📁 Files

- `workflow.json` — Full n8n workflow configuration

---

## 🙏 Acknowledgments

Special thanks to **Liyars** for the inspiring tutorial on building automation with AI and n8n.  
Watch the original video here: [Liyars | n8n | AI automation](https://www.youtube.com/watch?v=W9XMiKa1fe4)

---

> ⚡️ Made with ❤️ and n8n
