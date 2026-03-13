# lpepe-miner

🚀 Precompiled **ccminer** build optimized for **LPEPE mining** on NVIDIA GPUs.

This repository provides a simple and fast way to start mining **LPEPE** using a prebuilt miner package.

---

## Features

- ⚡ Optimized **ccminer build**
- 🧩 Simple installation
- 🐧 Compatible with most Linux distributions
- ⛏️ Ready for mining with one command
- 📦 Precompiled binary (no build required)

---

## System Requirements

- Linux (Ubuntu / Debian / HiveOS recommended)
- NVIDIA GPU with CUDA support
- Installed dependencies:
  - `libssl1.1`
  - `wget`
  - `tar`

---

## Quick Start

### 1. Download miner

```bash
wget -O lpepe.tar.gz https://raw.githubusercontent.com/iPepew/lpepe-miner/main/lpepe-miner.tar.gz
```

---

### 2. Install dependency (if needed)

Some systems may require **OpenSSL 1.1**:

```bash
apt update && apt install libssl1.1 -y
```

---

### 3. Extract archive

```bash
tar -xzf lpepe.tar.gz
cd lpepe-miner
```

---

### 4. Start mining

```bash
./start.sh YOUR_WALLET.WORKER
```

Example:

```bash
./start.sh lpep1qrj94ws0em8jy4hhekcpuglpnrc87fugfq95qj2.1pepe
```

Where:

| Parameter | Description |
|-----------|-------------|
| WALLET | Your LPEPE wallet address |
| WORKER | Worker name (any name) |

---

## Example HiveOS installation

Run the following commands inside your HiveOS worker:

```bash
wget -O lpepe.tar.gz https://raw.githubusercontent.com/iPepew/lpepe-miner/main/lpepe-miner.tar.gz
tar -xzf lpepe.tar.gz
cd lpepe-miner
./start.sh YOUR_WALLET.WORKER
```

---

## File Structure

```
lpepe-miner/
│
├── start.sh        # miner start script
├── ccminer         # compiled miner binary
└── README.md       # documentation
```

---

## Troubleshooting

### Missing library error

If you see an error like:

```
libssl.so.1.1: cannot open shared object file
```

Run:

```bash
apt update && apt install libssl1.1 -y
```

---

### Permission denied

Make the script executable:

```bash
chmod +x start.sh
```

---

## Security Notice

Always review scripts before running them on your system.

---

## Disclaimer

This project is provided **for educational and experimental purposes**.  
Use at your own risk.

---

## Contributing

Pull requests and suggestions are welcome.

---

## License

MIT License

# 🐸 PepePow — Meme Token Community

If you enjoy meme coins and crypto communities, take a look at **PepePow**.

PepePow is a community-driven meme token inspired by the legendary Pepe culture and built around decentralization and fun in crypto.

Main goals of the project:

* strong crypto community
* meme culture
* decentralized development
* fun and creativity in blockchain

All important project links are collected here:

👉 https://taplink.cc/pepepow

Join the Russian Telegram community:

👉 https://t.me/pepepow_ru

---

# 🐸 PepePow — Мем токен

Если вам нравятся мем-монеты и крипто-комьюнити — обратите внимание на **PepePow**.

Это мем-токен, созданный сообществом вокруг культуры Pepe и крипто-энтузиастов.

Основные идеи проекта:

* развитие крипто-сообщества
* мем-культура
* децентрализация
* весёлый подход к криптовалюте

Все основные ссылки проекта:

👉 https://taplink.cc/pepepow

Телеграм-сообщество:

👉 https://t.me/pepepow_ru
