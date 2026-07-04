# Real-Time-Algorithmic-Trading-Bot-

A production-ready **Algorithmic Trading Bot** built with **Python** and the **Upstox API**, designed to automate options trading in the Indian stock market. The bot executes predefined trading strategies with real-time market data, intelligent risk management, automated order execution, and continuous position monitoring. It features a modular architecture that supports multiple strategies, WebSocket-based live market streaming, secure authentication, persistent data storage, and automated trade management for reliable and efficient trading.

---

https://github.com/user-attachments/assets/14b87273-f655-45cf-bcc1-bee7f3293d90



## 🚀 Features

- 📈 Automated Options Trading
- ⚡ Real-Time Market Data (WebSocket)
- 🔐 Secure Upstox API Authentication
- 📊 Live Position Monitoring
- 💹 Real-Time Profit & Loss Tracking
- 🎯 Multi-Strategy Support
- 🛡 Risk Management Engine
- 🔄 Automatic Order Execution
- 📡 Automatic Reconnection
- 💾 SQL Database Support
- 📝 Trade Logging
- 🔔 Notifications & Alerts
- ⚙️ Configurable Trading Parameters

---

## 🏗 Architecture

```
Market Data
      │
      ▼
WebSocket Manager
      │
      ▼
Strategy Engine
      │
      ▼
Risk Manager
      │
      ▼
Order Manager
      │
      ▼
Upstox API
      │
      ▼
Database & Logs
```

---


## ✨ Core Modules

### Authentication
- Secure API authentication
- Access token management
- Session handling

### WebSocket Manager
- Singleton WebSocket connection
- Live market streaming
- Automatic reconnect
- Dynamic subscriptions

### Strategy Engine
- Multiple concurrent strategies
- Signal generation
- Position management
- Strategy lifecycle control

### Order Manager
- Buy/Sell execution
- Order modification
- Order cancellation
- Position synchronization

### Risk Management
- Stop Loss
- Target Profit
- Maximum Daily Loss
- Position Limits
- Trade Validation

### Database
- Trade history
- Orders
- Positions
- Strategy state
- User settings
- Logs

---

## 📊 Supported Trading Features

- Options Trading
- Futures Trading
- Live Positions
- Multi-Leg Strategies
- Hedge Positions
- Strategy Automation
- Portfolio Monitoring
- Real-Time Analytics

---

## ⚙️ Technologies Used

- Python
- Upstox API
- WebSockets
- SQLite / PostgreSQL
- SQLAlchemy
- Pandas
- NumPy
- Asyncio
- Logging

---

## 🔑 Configuration

Create a `.env` file

```text
UPSTOX_API_KEY=YOUR_API_KEY
UPSTOX_API_SECRET=YOUR_API_SECRET
UPSTOX_ACCESS_TOKEN=YOUR_ACCESS_TOKEN
DATABASE_URL=sqlite:///trading.db
```

---

## ▶️ Run the Bot

```bash
python main.py
```

---

## 📈 Workflow

1. Authenticate with Upstox API
2. Start WebSocket connection
3. Subscribe to market instruments
4. Receive live market data
5. Execute strategy logic
6. Validate risk parameters
7. Place orders automatically
8. Monitor open positions
9. Manage exits and square-offs
10. Store trades and logs

---

## 🛡 Risk Management

- Position Size Validation
- Maximum Loss Limits
- Stop Loss Protection
- Profit Target Management
- Duplicate Order Prevention
- Order Retry Mechanism
- Real-Time Position Monitoring

---

## 📊 Logging & Monitoring

- Order Logs
- Trade Logs
- Error Logs
- WebSocket Status
- Strategy Status
- Execution Reports

---

## 🔮 Future Enhancements

- Background Service
- Portfolio Analytics
- Multi-Broker Support
- Performance Reports

---


