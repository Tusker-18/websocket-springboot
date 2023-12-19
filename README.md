# Simple Spring Boot WebSocket Application

This is a simple Spring Boot application demonstrating WebSocket communication. It includes a basic WebSocket server that allows clients to send and receive messages.

## Prerequisites

- Java 8 or higher
- Maven


"The WebSocket server will start at http://localhost:8080."


## Usage


1. Open your browser and navigate to http://localhost:8080.  
2. Open the browser console to see WebSocket messages.  
3. Open multiple browser tabs or different browsers to simulate multiple users.  
4. Send messages between tabs or browsers to see real-time communication.  

## Project Structure
**src/main/java/com/example/greetingserver/config** : WebSocket configuration.  
**src/main/java/com/example/greetingserver/controller** : Controller handling WebSocket messages.  
**src/main/java/com/example/greetingserver/model** : POJOs representing WebSocket messages.  
**src/main/resources/static** : contains html,css and js.  

## WebSocket Endpoints
WebSocket Endpoint: **ws://localhost:8080/ws**  
Stomp Endpoint: **/ws**  
Application Destination Prefix: **/app** 
