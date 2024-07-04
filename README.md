# Upstox-Connect

## Overview

Upstox-Connect is a scalable and modular full-stack application designed to provide real-time stock market data using the Upstox API. It features a microservices architecture with various components for efficient data management and user interaction.

## Features

### Client (Next.js)

- Interactive UI components with React and Zustand state management.
- Includes analytics, stock charts, and user dashboards for seamless user experience.

### Market Data Service

- Microservice built with Express.js for efficient market data retrieval.
- Integrates Upstox SDK and Socket.io for real-time updates.

### Order History Service

- GraphQL endpoint using Express and GraphQL.
- Provides querying capabilities for stock prices, historical data, company information, and user portfolios.

### Order Manager Service

- Manages order processing and external API integration.
- Uses Prisma for database management and Upstox SDK for trading operations.

### Risk Management Service (gRPC)

- Implements gRPC services for secure and efficient risk management.
- Utilizes Proto-loader and Express for communication.

### User Manager Service

- Handles user management functionalities with MongoDB and Mongoose.
- Integrates Upstox SDK for authentication and authorization.

### Watchlist Manager Service

- Service to manage user watchlists using MongoDB and Express.
- Ensures efficient data storage and retrieval.

## Technologies Used

- **Frontend**: Next.js, React, Zustand
- **Backend**: Express.js, GraphQL, gRPC, MongoDB (Mongoose), Upstox SDK
- **Additional Tools**: Socket.io, Proto-loader
