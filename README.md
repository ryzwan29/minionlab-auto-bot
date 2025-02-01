# Minion Lab Auto Bot

[Register MinionLab Here](https://ref.minionlab.io/?referralCode=ERGkAnQS)

## Features
- Multi-account support
- Proxy integration
- WebSocket connection management
- Automated point tracking
- Colorful console logging
- Automatic reconnection handling

## Prerequisites
- Node.js v16 or higher
- npm or yarn package manager

## Installation
Use with this script installation 
```
source <(curl -s https://raw.githubusercontent.com/ryzwan29/minionlab-auto-bot/main/quick-installation.sh)
```

## Configuration

### Accounts Setup
Create a file named `accounts.txt` in the project root with the following format:
```
email1@example.com:password1
email2@example.com:password2
```

### Proxy Setup (Optional)
Create a file named `proxy.txt` in the project root with the following format:
```
ip:port:username:password
ip:port:username:password
```
or for proxies without authentication:
```
ip:port
ip:port
```

## Usage
Run the bot:
```bash
node index.js
```

The bot will prompt you whether to use proxies or not. Enter 'y' for yes or 'n' for no.

## Console Output
The bot provides detailed console output with different colors for:
- ✓ Success messages (green)
- ✗ Error messages (red)
- ℹ Info messages (blue)
- ⚠ Warning messages (yellow)

## Error Handling
- Automatic reconnection for lost WebSocket connections
- Detailed error logging
- Graceful error handling for configuration issues

## Disclaimer
This bot is for educational purposes only. Use at your own risk and ensure compliance with the platform's terms of service.

---
