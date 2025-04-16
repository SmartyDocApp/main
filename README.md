# Smarty_Doc_APP

## Project Overview
SGDI (Système de Gestion Documentaire Intelligent) transforms traditional document management into a complete cognitive social ecosystem. The platform bridges the gap between personal knowledge management tools (like Notion, Obsidian, Evernote) and collaborative environments by providing an intelligent approach to document organization, analysis, and collaboration.

## Current Implementation (Phase 1)
The foundation of SGDI delivers a modern document management platform with:

Intuitive user interface with light/dark mode support
Document upload/download with preview capabilities
Manual categorization and tagging system
Full-text search functionality
Hybrid SQL/NoSQL architecture (MySQL for metadata, MongoDB for content)
User management with role-based access controls
Collaborative workspaces with integrated text chat
Bidirectional document sharing between personal space and workspaces

## Technical Architecture

Frontend: React application with TypeScript, Redux, and modern React patterns
Backend: RESTful API using Spring Boot microservices architecture
Storage: Hybrid data model leveraging MySQL and MongoDB
Infrastructure: Docker containers orchestrated with Kubernetes
Real-time Communication: WebSockets for chat functionality
CI/CD: Automated pipelines with GitHub Actions
