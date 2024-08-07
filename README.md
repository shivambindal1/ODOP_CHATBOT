
# Zuzu: The ODOP Chatbot 🤖🇮🇳

Welcome to **Zuzu**, the ODOP (One District One Product) chatbot! Zuzu provides information about unique products from every district across India, using Botpress for an interactive and user-friendly experience. All data is accessible in PDF format via an online link.

## 📑 Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Features](#features)
4. [Installation](#installation)
5. [Configuration](#configuration)
6. [Usage](#usage)
7. [Data Structure](#data-structure)
8. [Customization](#customization)
9. [Contributing](#contributing)
10. [FAQ](#faq)
11. [License](#license)
12. [Contact](#contact)

## 🌟 Introduction

India is a land of diverse cultures and unique products. The ODOP initiative aims to promote these products from each district, boosting local economies and preserving cultural heritage. **Zuzu**, our chatbot, helps users discover these products through engaging conversations and detailed information, accessible online.

## 📜 Project Overview

Zuzu is designed to support the ODOP initiative by providing detailed information about products from every district in India. Built using Botpress, Zuzu offers a seamless and interactive experience to explore and learn about India’s rich heritage.

## ✨ Features

- **Interactive Conversations**: Engage with Zuzu through natural language.
- **Comprehensive Data**: Information about products from all districts in India.
- **User-Friendly Interface**: Smooth and intuitive chatting experience.
- **Emoji Support**: Expressive and fun interactions.
- **PDF Data Access**: Information available in PDF format via an online link.

## 🛠️ Installation

Follow these steps to set up Zuzu:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/zuzu-odop-chatbot.git
   cd zuzu-odop-chatbot
   ```

2. **Install Dependencies**:
   Ensure Node.js and npm are installed. Then, install Botpress CLI:
   ```bash
   npm install -g @botpress/cli
   ```

3. **Start Botpress**:
   Navigate to the Botpress directory and start the Botpress server:
   ```bash
   cd botpress
   bp
   ```

4. **Import Zuzu Bot**:
   Import the Zuzu bot configuration via the admin interface:
   - Visit the Botpress admin panel.
   - Navigate to "Modules" and import bot configuration files from the `config` directory.

5. **Run the Chatbot**:
   Access Zuzu via your preferred link:
   ```bash
   http://your-deployment-link
   ```

## ⚙️ Configuration

To configure Zuzu:

1. **Bot Configuration**:
   Adjust bot settings in the `botpress/config` directory for language, interaction behavior, and appearance.

2. **Environment Variables**:
   Set up necessary environment variables in a `.env` file at the root of your project.

Example `.env` file:
```env
BPFS_STORAGE=local
DATA_URL=https://your-data-link.com
```

## 🎮 Usage

Once running, interact with Zuzu through the chat interface. Here are some sample commands:

- **General Greeting**: "Hi Zuzu!" 👋
- **Product Inquiry**: "Tell me about the product from Agra."
- **District Information**: "What is the ODOP product of Jaipur?"
- **Historical Facts**: "Share some historical facts about Varanasi's product."

Zuzu responds with relevant information, using emojis to enhance the experience.

### Example Interactions

**User**: Hi Zuzu! 👋  
**Zuzu**: Hello! 😊 How can I assist you today? Ask me about any ODOP product from across India.

**User**: Can you tell me about the product from Agra?  
**Zuzu**: Sure! Agra is famous for its delicious Petha. 🍬 It's a sweet delicacy made from ash gourd and has been a traditional sweet in Agra for centuries.

## 🗂️ Data Structure

Data for each district is stored in PDF format, accessible via a link. Each PDF contains:

- `District Name`: Name of the district
- `Product Name`: Name of the product
- `Description`: Detailed description
- `Historical Background`: Historical significance
- `Commercial Info`: Commercial details and statistics
- `Emoji`: Relevant emojis representing the product

## 🎨 Customization

To customize Zuzu:

1. **Edit Data**: Update PDF files with new or modified product information.
2. **Update Flows**: Use the Botpress admin interface to tweak conversational flows and responses.
3. **Add Emojis**: Enhance responses with additional emojis.

## 🤝 Contributing

We welcome contributions to improve Zuzu! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.

## ❓ FAQ

### What is ODOP?
ODOP stands for One District One Product, an initiative to promote unique products from each district in India.

### How can I add new products to Zuzu's database?
Update the PDF files with new product information and ensure the data link is updated.

### Can Zuzu support multiple languages?
Yes, Zuzu can be configured to support multiple languages via the Botpress admin interface.

### How do I update Zuzu?
Pull the latest changes from the repository and restart the Botpress server. Backup your data before performing updates.

