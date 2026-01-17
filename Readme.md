# 🗃️ Obsidian Base Hub

![Version](https://img.shields.io/badge/version-2.2.0-blue)
![Obsidian](https://img.shields.io/badge/Obsidian-native%20Bases-purple)
![License](https://img.shields.io/badge/license-MIT-green)

> A modular Obsidian vault leveraging native Bases to replicate Notion-like database functionality for personal project and task management.

## 📋 Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Who Is This For](#who-is-this-for)
- [Getting Started](#getting-started)
- [Vault Structure](#vault-structure)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Author](#author)
- [License](#license)

## 🎯 Overview

**Obsidian Base Hub** is a comprehensive vault template built on the **KISS principle** (Keep It Simple, Stupid) that transforms Obsidian into a powerful project management system. It provides interconnected databases similar to Notion, specifically designed for managing complex and dynamic work environments.

Unlike team management tools, this system focuses on **individual workflow optimization** while maintaining flexibility for evolving project requirements.

## ✨ Key Features

### 📥 Inbox Management
Quick capture system for unstructured notes that can be processed into appropriate databases later.

### 📊 Data Management
- **People Database**: Document work relationships and colleagues
- **Meetings System**: Organized note-taking and meeting coordination
- **(New) Location Database**: Easily locate all your contacts and meetings
- **Daily Journal**: Track daily work progress and achievements

### ⚙️ Work Management
- **Task System**: Break down work into minimal units with global progress states and priorities

### 🚀 Development Control
- **Projects Database**: Time-bound development initiatives with beginning and end
- **Areas Database**: Ongoing permanent work streams
- **Centralized Information**: Each project and area maintains its own database for tasks, team members, and meetings without content duplication

## 👥 Who Is This For

This vault is ideal for:
- Professionals working in dynamic and changing environments
- Consultants managing multiple concurrent projects
- Developers and knowledge workers needing robust personal project management
- Anyone seeking a Notion alternative with local control and Obsidian's power

## 🚀 Getting Started

### Prerequisites
- Obsidian with native Bases feature support
- Basic understanding of Obsidian properties and templates

### Installation

1. **Clone this repository**
2. **Open in Obsidian**
- Launch Obsidian
- Select "Open folder as vault"
- Choose the cloned repository folder

### Initial Setup

1. **Register Projects and Areas**
- Follow the steps in `ℹ️ Projects` and `ℹ️ Areas` notes

2. **Populate People Database**
- Complete your contacts in `ℹ️ People`

1. **Configure Templates and routes**
- Go to Settings > Templates
- Set `999 - Templates` folder as template directory
- Set `998 - Attachments` folder as template attachment directory 
- Use "Insert template" button (📄 icon) when creating Meetings or People

4. **Setup Daily Notes**
- Go to Settings > Daily notes
- Configure new file location: `050 - Daily / Items`
- Set base template: `999 - Daily note`

5. **Customize Properties**
- Add custom properties to match your specific work context

## 📁 Vault Structure

```
├── 010 - Inbox/ # Quick capture notes  
├── 020 - Projects/ # Time-bound projects  
├── 030 - Areas/ # Ongoing work areas  
├── 040 - Tasks/ # Task management
├── 050 - Daily/ # Daily journal  
├── 060 - Meetings/ # Meeting notes  
├── 070 - People/ # Contacts database    
├── 998 - Attachments/ # Attachments directoy   
└── 999 - Templates/ # Note templates
```

## ⚙️ Configuration

The vault is pre-configured with sensible defaults, but you can customize:
- Properties to match your workflow
- Templates for different note types
- Database views and filters
- Folder structure (though recommended to keep as-is)

## 👤 Author

**Rafa Campos**
- Product design unicorn 🦄
- Specializing in information management systems for projects and businesses
- Available for consultations and custom implementations
- Contact: flowmaxime@gmail.com

## 📄 License

This project is licensed under the MIT License

---

**Note**: This vault requires Obsidian's native Bases feature. Make sure you're using a compatible version of Obsidian.

⭐ If you find this vault useful, please consider starring the repository!
