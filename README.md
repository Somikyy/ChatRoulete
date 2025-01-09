# Textual Chatroulette

## Project Description

Textual Chatroulette is a web application for anonymous real-time communication. Users can choose a nickname each time they connect, join chat rooms, and interact with other participants. The system is integrated with Discord to store messages and synchronize chats.

## Main Features:
- **Anonymous Login**: Each user can choose a new nickname each time they connect.
- **Chat Rooms**: Create and participate in rooms with a participant limit.
- **Real-Time**: Instant message delivery between users.
- **Redis for Message Delivery**: Redis is used to deliver messages from users to the Discord bot.
- **Discord Integration**: The Discord bot sends messages to the corresponding chat rooms as embedded messages and synchronizes them among all participants in the room.
- **Logs and Security**: Users' IP addresses are stored to prevent offenses (such as harassment) and block offenders.

## Technology Stack:
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **WebSocket**: Used to ensure real-time message exchange between users.
- **Redis**: Used as a message broker for transmitting data between clients and the Discord bot.
- **Discord Bot**: Stores and synchronizes messages between participants in chat rooms.

## Workflow Diagram:
1. The user sends a message.
2. The message is sent via Redis to the Discord bot.
3. The Discord bot posts the message in the corresponding chat room.
4. All participants in the room receive the updated messages in real time.

## Project Objectives:
- Provide anonymous and secure communication to users.
- Create a simple and convenient platform for real-time communication.
- Use Redis for efficient message delivery and chat synchronization via the Discord bot.

## Developers:
This project is being developed by two developers:
- [Somikyy's GitHub]([https://github.com/developer1](https://github.com/Somikyy))
- [Cbaie9 GitHub]([https://github.com/developer2](https://github.com/cbaie9))
