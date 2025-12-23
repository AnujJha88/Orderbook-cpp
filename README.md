# Trading System

A C++17 trading system with WebSocket connectivity for order management and market data streaming.

## Features

- Real-time order management
- WebSocket-based communication
- Support for multiple order types
- Position tracking
- Market data streaming
- Interactive TUI (Text-based User Interface) using FTXUI

## Prerequisites

- C++17 compatible compiler (GCC/Clang)
- CMake 3.14+
- Boost libraries (system, thread, ssl, crypto)
- OpenSSL
- nlohmann/json

## Building

1. Clone the repository:

   ```bash
   git clone git@github.com:AnujJha88/Orderbook-cpp.git
   cd Orderbook-cpp
   ```
2. Build the project:

   ```bash
   make
   ```

## Configuration

1. Create a `.env` file with your Deribit API credentials:
   ```
   API_KEY=your_api_key_here
   API_SECRET=your_api_secret_here
   ```

## Running

```bash
make run
```

## Project Structure

- `OrderManager.h/cpp` - Handles order management
- `Order.h/cpp` - Order data structure
- `Authenticator.h/cpp` - Handles API authentication
- `menu.h/cpp` - Text-based user interface
- `orderbook.cpp` - Main application entry point

## License

[Apache 2.0]
