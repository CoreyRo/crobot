# Crobot

<div align="center">
  <img src=".github/images/logo-landscape.png" alt="Crobot Logo" width="400">
</div>

A modern Discord bot platform with AI-powered features, content aggregation, and subscription management. Built with a scalable microservices architecture and a beautiful web interface for configuration and management.

## Project Status

### Backend
[![CI](https://github.com/CoreyRo/crobot-backend/actions/workflows/ci.yml/badge.svg)](https://github.com/CoreyRo/crobot-backend/actions/workflows/ci.yml)
[![Test and Coverage](https://github.com/CoreyRo/crobot-backend/actions/workflows/test-and-coverage.yml/badge.svg)](https://github.com/CoreyRo/crobot-backend/actions/workflows/test-and-coverage.yml)
[![Codecov](https://codecov.io/gh/CoreyRo/crobot-backend/branch/main/graph/badge.svg)](https://codecov.io/gh/CoreyRo/crobot-backend)
[![Coverage](https://img.shields.io/codecov/c/github/CoreyRo/crobot-backend)](https://codecov.io/gh/CoreyRo/crobot-backend)

### Frontend
[![Test](https://github.com/CoreyRo/crobot-web/actions/workflows/test.yml/badge.svg)](https://github.com/CoreyRo/crobot-web/actions/workflows/test.yml)
[![Deploy](https://github.com/CoreyRo/crobot-web/actions/workflows/deploy.yml/badge.svg)](https://github.com/CoreyRo/crobot-web/actions/workflows/deploy.yml)
[![Codecov](https://codecov.io/gh/CoreyRo/crobot-web/branch/main/graph/badge.svg)](https://codecov.io/gh/CoreyRo/crobot-web)
[![Coverage](https://img.shields.io/codecov/c/github/CoreyRo/crobot-web)](https://codecov.io/gh/CoreyRo/crobot-web)

## About

Crobot is a comprehensive Discord bot platform that combines AI-powered chat capabilities with intelligent content aggregation and distribution. The platform is designed for scalability, maintainability, and extensibility, featuring a microservices architecture that separates concerns across multiple specialized services.

### Key Features

- **AI-Powered Chat** - Interactive AI conversations with support for multiple AI providers
- **Content Aggregation** - Automated ingestion from Reddit, news APIs, and RSS feeds
- **Smart Content Routing** - Intelligent clustering and distribution of discovered content
- **Subscription Management** - Tiered subscription system with feature gating
- **Multi-Guild Support** - Scalable architecture supporting multiple Discord servers
- **Web Dashboard** - Modern React-based interface for bot configuration and user management
- **OAuth Integration** - Seamless authentication via Discord and Patreon OAuth2

## Architecture

Crobot follows a microservices architecture with clear separation of concerns:

- **Gateway Service** - Discord bot gateway handling interactions, commands, and sharding
- **Worker Services** - Background processing for content ingestion, routing, and posting
- **API Services** - RESTful APIs for operational monitoring and web backend
- **Web Frontend** - React SPA for user-facing configuration and management
- **Core Domain** - Pure domain models with zero dependencies
- **Infrastructure** - Data access, repositories, and external integrations

## Technology Stack

### Backend
- **.NET 10.0** - Modern C# runtime and framework
- **Discord.NET** - Discord bot framework with sharding support
- **Entity Framework Core** - ORM with PostgreSQL database
- **Serilog** - Structured logging and observability
- **Docker** - Containerization for all services
- **xUnit + NSubstitute** - Comprehensive testing framework

### Frontend
- **React 18** - Modern UI framework
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool and dev server
- **Material-UI (MUI)** - Professional component library
- **Tailwind CSS** - Utility-first styling
- **Jest + React Testing Library** - Testing framework

### DevOps
- **GitHub Actions** - CI/CD pipelines
- **Codecov** - Code coverage tracking
- **Docker Compose** - Multi-service orchestration
- **Netlify** - Frontend hosting and deployment

## Project Structure

This repository serves as the public-facing documentation and overview of the Crobot platform. The implementation is split across private repositories:

- **Backend** - Microservices architecture, APIs, and Discord bot implementation
- **Web** - React frontend application for user management and configuration

## License

See [LICENSE.md](LICENSE.md) for details.
