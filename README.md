# Chat Application

A real-time chat application built with **Spring Boot**, **Thymeleaf**, **WebSockets**, and **STOMP** for instant messaging.

## Features

**Real-time Messaging**: Instant communication using WebSockets and STOMP.
**User-Friendly Interface**: Frontend built with Thymeleaf and JavaScript.
**Group & One-on-One Chats**: Supports both private and group conversations.
**Message History**: Stores chat messages.
**Delivery Receipts**: Indicators for sent and received messages.
**Lightweight & Fast**: Uses STOMP for efficient communication.

## Technologies Used

**Backend**: Spring Boot, Spring Web, Spring WebSocket, STOMP
**Frontend**: Thymeleaf, JavaScript

## Installation & Setup

## Prerequisites

 Java 17+ installed
 Maven installed

## Steps to Run the Application

1. **Clone the repository**

   git clone https://github.com/dsarkar6575/Chat-Application.git
   cd Chat-Application

2. **Build and run the application**

   mvn spring-boot:run
   
3. **Access the application**
   Open your browser and go to: `http://localhost:8080/chat`

## WebSocket and STOMP Integration

  Uses WebSockets with STOMP protocol for real-time messaging.
  JavaScript connects to the WebSocket endpoint using `SockJS` and `Stomp.js`.





