# Portfolio of Fatma
👋 Hi! I'm a software developer passionate about building modern mobile applications, backend APIs, and AI-powered applications. I enjoy developing mobile experiences using **Kotlin, Jetpack Compose, Flutter, and Dart**, with a focus on clean UI and maintainable code. I'm also expanding my backend development skills with **Java, Spring Boot, C#, .NET, ASP.NET Core, and SQL Server**, exploring layered architecture, authentication, RESTful API development, and maintainable backend design. 🤖 In AI development, I work with **Python, FastAPI, LangGraph, and LLMs** to build intelligent assistants that use tools and conversational memory to provide more useful responses.

🚀 I'm always learning, building projects, and exploring new technologies. Feel free to explore my work and connect with me!


# 🎵 [Spotify Clone — Android App (Jetpack Compose)](https://github.com/FatmaJxx/portfolio/blob/main/spotify-clone-architecture.md)

A full-stack Spotify-inspired application built with Kotlin, Jetpack Compose, and a Spring Boot backend. The project focuses on modular Android architecture, secure authentication, encrypted session storage, and communication with a REST API.

✨ **Key Features:**
- 🔐 Authentication flow with Login, Sign Up, and passwordless magic-link authentication
- 🔑 JWT-based authentication with automatic access-token refresh
- 🔒 Encrypted local session storage using Proto DataStore and Android Keystore
- 🌐 REST API integration with Retrofit and OkHttp
- 🔄 Centralized authentication headers, retry handling, and token refresh logic
- ✅ Reusable form validation with a multi-step registration flow
- 🧱 Modular architecture separating core components and feature modules
- 📱 Lifecycle-aware UI state management with Kotlin Flow and Jetpack Compose
- 📐 Adaptive Home screen layout for phones, foldables, and tablets — in progress

🛠️ **Built With:**

**Android:**
- Kotlin
- Jetpack Compose & Material 3
- Hilt
- Kotlin Coroutines & Flow
- Navigation Compose
- Proto DataStore
- Android Keystore
- Retrofit & OkHttp

**Backend:**
- Java
- Spring Boot
- JWT Authentication
- PostgreSQL

🏗️ **Architecture Highlights:**
- Modular architecture with shared core modules and independent feature modules
- Repository pattern separating UI features from network implementations
- Custom authentication interceptors and token authenticator
- Encrypted session persistence with Android Keystore-backed cryptography
- Centralized dependency injection and reusable UI components

🚧 **Work in Progress** — Developing the Home experience, adaptive navigation, and additional Spotify-inspired features.

🔗 [View Architecture Documentation](https://github.com/FatmaJxx/portfolio/blob/main/spotify-clone-architecture.md)


![Image](https://github.com/user-attachments/assets/4c231ec2-5a06-43e8-85c3-555f24407c7b)


# 🐦 Twitter / X Clone — Flutter App

A Twitter-inspired mobile application built with Flutter, combining a familiar microblogging experience with an AI-powered chat assistant.

✨ **What's included so far:**
- 🔐 Authentication UI with Login and Sign Up screens
- 🏠 Home feed displaying tweets using local dummy data
- 🤖 AI-powered chat screen integrated with Firebase AI (Gemini)
- 🖼️ Multimodal conversations supporting text and image attachments
- 🎨 Function calling that enables the assistant to generate images on request

🏗️ **Architecture & Design:**
- BLoC for state management
- Repository pattern and use cases
- Clean Architecture principles
- AI chat functionality organized in an independent, decoupled module

🛠️ **Built With:**
- Flutter
- Dart
- Firebase
- Firebase AI (Gemini)
- BLoC
- Clean Architecture

🚧 **Still in progress** — Profile screen, search, notifications, and additional social features are planned for future development.


![Image](https://github.com/user-attachments/assets/7cef5eba-7fb5-4d5c-924f-956388f9ee22)


# 🤖 [Telegram AI Chatbot](https://github.com/FatmaJxx/telegram-ai-chatbot)
A production-ready AI assistant delivered via Telegram, built with a modern Python backend stack. The bot understands natural language and uses tools to give accurate, real-time answers — not just LLM guesses.

✨ What it can do:
* 🧠 User-specific data and conversation memory
* 📄 Document reading and processing
* 📅 Google Calendar integration
* 🌤️ Live weather lookup
* 🧮 Math calculations
* 📖 Wikipedia search
* 🕐 Date & time tools

🛠️ Built With:
* Python & FastAPI
* LangGraph (agent loop with tool use)
* Gemini (Google Generative AI)
* MongoDB (persistent conversation memory)
* Telegram Bot API

🧠 How it works:
Instead of asking the LLM to guess answers, the agent decides which tool to call, runs it, reads the result, then replies — a proper ReAct loop built with LangGraph.

🚧 More tools coming soon — web search, reminders & more!

[🔗 View Repository](https://github.com/FatmaJxx/telegram-ai-chatbot)


<img width="1920" height="1080" alt="telegram-bot" src="https://github.com/user-attachments/assets/ff07872c-6f46-4403-bf87-b91f809be737" />


# 🖥️ [TwitterBackend — .NET Web API](https://github.com/FatmaJxx/TwitterBackend)

A Twitter-inspired backend API built with C# and .NET 10, focusing on layered architecture, authentication, request validation, and reusable application infrastructure.

✨ **Key Features:**
- 🔐 JWT authentication with access and refresh tokens
- 🏗️ Layered architecture separating Web API, Application, Domain, and Infrastructure
- 🔄 Custom Mediator implementation with pipeline behaviors
- ✅ Request validation using FluentValidation
- 🛡️ Centralized exception handling and request logging
- 🔒 Transaction and idempotency behaviors
- 🗄️ Entity Framework Core with Microsoft SQL Server
- ⚡ CancellationToken support for asynchronous operations

🛠️ **Built With:**
- C#
- .NET 10 / ASP.NET Core
- Entity Framework Core
- Microsoft SQL Server
- FluentValidation
- JWT Bearer Authentication

🏛️ **Architecture:**

The solution follows a layered architecture, with a custom mediator and pipeline behaviors to centralize cross-cutting concerns such as validation, logging, exception handling, transactions, and idempotency.

🚧 **Work in Progress** — Continuing to improve authentication flows, testing, and backend functionality.

[🔗 View Repository](https://github.com/FatmaJxx/TwitterBackend)

