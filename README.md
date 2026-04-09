# 💬 Cloudflare + Flutter Real-time Chat

A full-stack real-time chat application built with **Flutter** for the mobile frontend and **Cloudflare Workers (Durable Objects)** for the backend.

## 🏗️ Project Structure
- **/backend**: TypeScript Cloudflare Worker handling WebSockets and message persistence via Durable Objects.
- **/flutter_app**: Mobile client built with Flutter using `web_socket_channel` for real-time communication.

## 🚀 Getting Started

### Backend (Cloudflare)
1. Navigate to the backend: `cd backend`
2. Install dependencies: `npm install`
3. Run locally: `npx wrangler dev`
   - The server will start on `http://127.0.0.1:8787`

### Frontend (Flutter)
1. Navigate to the app: `cd flutter_app`
2. Get packages: `flutter pub get`
3. Run the app: `flutter run`
   - *Note: If using Android Emulator, point the API to `10.0.2.2:8787`.*

## 🛠️ Features
- [x] Serverless Backend (Cloudflare Workers)
- [x] Real-time Messaging (WebSockets)
- [ ] Message History (D1 Database) - *Coming Soon*
- [ ] User Authentication - *Coming Soon*

## 📝 Learning Log
- **2026-04-09:** Initialized Monorepo, set up Cloudflare Worker with TypeScript, and connected initial local environment.
