# MesArat

MesArat is a secure messenger with encryption, digital signatures, and real-time communication. The project is built on a modern technology stack and consists of two main parts — frontend and backend.

---

## 🔗 Repository Structure

This repository combines both parts as submodules:

- 🧩 **frontend** — client application built with React, TypeScript
- 🧩 **backend** — server application built with NestJS, GraphQL, PostgreSQL, Redis, and S3 storage

---

## 🚀 Key Features

- 👤 User registration and login
- 💬 Creating and participating in chats and groups
- ✉️ Sending messages and files with support for attachments
- ❌ Deleting messages
- 🔔 Notifications for new messages and events
- 🕒 Real-time updates via GraphQL subscriptions

---

## 🧠 Technology Stack

### Frontend

- React + Next.js + TypeScript
- Apollo Client (GraphQL)
- TailwindCSS

### Backend

- NestJS + GraphQL
- PostgreSQL + Prisma ORM
- Redis for session management
- Selectel S3 for file storage
- Authorization via decorators and guards

---

MesArat is a privacy-first messaging platform built from scratch with custom cryptography and a secure real-time communication architecture.
