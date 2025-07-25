# Project Blueprint

## Overview

This is a basic Flutter application created with Firebase Studio. It currently features a counter on the home page and navigation to a chatbot page.

## Implemented Features

- **Counter Home Page:** A basic home page with a counter that can be incremented.
- **Chatbot Page:** A new page for a chatbot interface, including a text input and a message display area.
- **REST API Call:** Integration of a function to call a REST endpoint from the chatbot page using the `http` package.
- **Navigation:** Navigation from the home page to the chatbot page.

## Plan for Current Change: Create Chatbot Page and Call REST Endpoint

- Create a new Dart file (`lib/chatbot_page.dart`) for the chatbot UI and logic.
- Design the chatbot interface with a text input and message list.
- Implement a function to call a REST endpoint for sending and receiving messages.
- Add the `http` dependency to `pubspec.yaml`.
- Update `lib/main.dart` to include navigation to the chatbot page.
