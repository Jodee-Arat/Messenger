MesArat is a secure messenger with encryption, digital signatures, and real-time communication. The project is built on a modern tech stack and split into two parts — frontend and backend.

🔗 This repository combines both components as submodules:

🧩 frontend — client application built with React + TypeScript + DES/DH/RSA

🧩 backend — server application with NestJS + GraphQL + PostgreSQL + Redis + S3

🚀 Key Features
👤 User registration and login

💬 Creating and participating in chats

✉️ Sending messages and files

📎 Support for attachments (sending text and files together)

❌ Message deletion

🔔 Notifications for new events

🕒 Real-time updates via GraphQL Subscriptions

🛡️ Cryptography and Security
The project uses a hybrid cryptography approach, mainly implemented on the client side:

🔐 DES — symmetric encryption for messages and files

🔄 Diffie-Hellman — secure key exchange for DES keys between users

✍️ RSA — digital signatures to verify message authenticity

🔒 All data is encrypted before sending and decrypted only on the client

🧠 Technology Stack
🌐 Frontend:
React + Next.js + TypeScript

Apollo Client (GraphQL)

TailwindCSS

Web Crypto API (DES)

Custom DH and RSA implementations

⚙️ Backend:
NestJS + GraphQL

PostgreSQL + Prisma ORM

Redis (session storage)

Selectel S3 (cloud file storage)

Authorization via decorators and guards

Entities: account, session, chat, cryptography

MesArat is a privacy-first project built from scratch with custom crypto implementations and a secure real-time data exchange architecture.
