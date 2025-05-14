# 📄 RFP Buddy

> Final project for a 14-week Full-Stack Bootcamp — Challenge by **Nagarro**

## 🚀 Project Overview

**RFP Buddy** is a smart assistant tool designed to support proposal creation by:

- ✅ Searching and suggesting the best snippets for new clients  
- ✅ Adjusting tone for different audiences  
- ❌ Storing and organizing past proposals (Not implemented yet)  
- ❌ Learning from history (Not implemented yet)

The application aims to increase productivity and consistency in drafting Request for Proposal (RFP) responses by utilizing intelligent search and AI-powered suggestions.

## 💡 Features

- 🔍 Contextual search of proposal snippets  
- ✍️ Tone adjustment for tailored messaging  
- 🧠 Integration with OpenAI for AI-powered text generation  
- ☁️ Cloud deployment using AWS

## 🛠️ Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring Data JPA** – for database interaction  
- **Hibernate** – ORM for Java  
- **PostgreSQL** – database (if configured, based on typical Spring setup)  
- **OpenAI API** – for AI-powered text generation  
- **AWS** – for deployment  
- **Maven** – build tool  
- **Lombok** – to reduce boilerplate code  
- **DTO Pattern** – for data transfer across layers  
- **Layered Architecture** – (Controller, Service, Repository, Model)

## 📁 Project Structure

```bash
rfp/
├── command/         # DTOs
├── controller/      # REST API Controllers
├── model/           # Data models
├── repository/      # Spring Data Repositories
├── service/         # Business logic
├── rag/             # Likely custom logic for Retrieval-Augmented Generation
├── RfpApplication.java  # Main Spring Boot Application Entry
```

## ⚠️ Note

> The deployment is currently **online**, but **functionality is limited** due to an expired OpenAI API key.  
> If you're interested in exploring the app, please [connect with me on LinkedIn](#) and I’ll provide access.
> Here you only have access to the source code of the RFP Buddy.
