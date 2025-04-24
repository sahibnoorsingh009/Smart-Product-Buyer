# Smart Product Buyer AI Agent 🚗🤖

## Overview

This project demonstrates a **Smart Product Buyer AI Agent**, built as a **Proof of Concept (PoC)** to assist users in making intelligent purchase decisions. The current version specializes in car purchases using AutoTrader data, but the architecture is designed to be easily extended to other product types and websites.

The system utilizes **LangGraph**, **LangChain**, and **LLM-based workflows** to create an intuitive, intelligent assistant that interacts with users to assess preferences, filter listings, and provide actionable insights.

---

## 🔍 Features

- **User Preference Understanding**: Interacts conversationally to assess buyer needs.
- **Dynamic Filter Creation**: Translates user preferences into search filters.
- **Web Scraping (AutoTrader)**: Retrieves real-time listings using Playwright and lxml.
- **Insight Generation**: Summarizes and provides recommendations based on listings.
- **Modular & Extendable**: Easily adaptable to more platforms or product domains.
- **Optional Gradio Interface**: Launch a GUI for easier interaction.

---

## 🧠 Architecture

The workflow includes:

1. **User Need Assessment**
2. **Filter Building**
3. **Web Data Retrieval**
4. **Insight Delivery**

