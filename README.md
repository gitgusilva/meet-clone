# Meet-Clone  

A Google Meet clone built with **Vue 3**, **TypeScript**, **NestJS**, **WebRTC**, and **Coturn**. This project enables seamless video conferencing with features like real-time video, audio, and chat support, leveraging WebRTC for peer-to-peer communication and Coturn for NAT traversal.

---

## Features
- **Real-Time Communication**: Video and audio calls using WebRTC.
- **NAT Traversal**: Coturn server integration to bypass NAT/firewall restrictions.
- **Scalable Backend**: Built with NestJS to handle signaling and room management.
- **Modern Frontend**: Vue 3 with TypeScript for a dynamic, reactive UI.
- **Chat Support**: Real-time text chat during calls.
- **Room Management**: Users can create, join, and manage meeting rooms.
- **Responsive Design**: Works seamlessly across devices.

---

## Tech Stack
- **Frontend**: Vue 3, TypeScript, WebRTC
- **Backend**: NestJS, Socket.IO
- **Server**: Coturn for STUN/TURN services
- **DevOps**: Docker (optional for deployment)

---

## Installation and Setup

### Prerequisites
- **Node.js** (>= 18.x)
- **Docker** (if running Coturn in a container)
- A domain (for secure HTTPS connections with WebRTC)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/gitgusilva/meet-clone.git
   cd meet-clone
