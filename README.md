# 🎭 Memecord

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![discord.py](https://img.shields.io/badge/discord.py-2.0+-blue.svg)](https://discordpy.readthedocs.io/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()

> A Python-powered Discord bot that delivers random memes from Reddit instantly. Built with discord.py and the Meme API.

## ✨ Features

- 🎯 **Instant Memes** - Type `$meme` and get random memes from Reddit
- ⚡ **Slash Commands** - Modern `/meme` command support
- 🚀 **Fast & Reliable** - Built with async Python for optimal performance
- 🔒 **Secure** - Environment variables for token management
- 🎨 **Clean Code** - Easy to understand and modify
- 🌐 **24/7 Deployment** - Hosted on Railway for continuous uptime

## 🎬 Demo

**Text Command:**
```
User: $meme
Bot: [Random meme image from Reddit]
```

**Slash Command:**
```
/meme
```

## 🛠️ Tech Stack

- **Python 3.8+**
- **discord.py 2.0+** - Discord API wrapper
- **requests** - HTTP library for API calls
- **python-dotenv** - Environment variable management
- **Meme API** - Reddit meme source (https://meme-api.com)
- **Railway** - Cloud deployment platform

## 📦 Installation

### Prerequisites
- Python 3.8 or higher
- Discord Bot Token ([Create one here](https://discord.com/developers/applications))
- Discord Server with admin permissions

### Quick Setup

**1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/memecord.git
cd memecord
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Configure environment variables**

Create a `.env` file in the root directory:
```env
DISCORD_TOKEN=your_bot_token_here
```

**4. Run the bot**
```bash
python bot.py
```

You should see:
```
Slash commands synced!
Logged in as YourBot#1234
Bot is ready and online!
```

## 🎮 Usage

### Commands

**Text Command:**
- `$meme` - Get a random meme from Reddit

**Slash Command:**
- `/meme` - Get a random meme from Reddit

### Inviting the Bot

1. Go to [Discord Developer Portal](https://discord.com/developers/applications)
2. Select your application
3. Go to **OAuth2 → URL Generator**
4. Select scopes: `bot`, `applications.commands`
5. Select permissions: `Send Messages`, `Use Slash Commands`
6. Copy the generated URL and open it in your browser
7. Select your server and authorize

## 📁 Project Structure

```
memecord/
│
├── bot.py              # Main bot code with slash commands
├── .env                # Environment variables (not in repo)
├── .gitignore          # Git ignore file
├── requirements.txt    # Python dependencies
├── Procfile           # Railway deployment config
└── README.md          # Project documentation
```

## 🔐 Security

- ✅ Bot token stored securely in `.env` file
- ✅ `.env` excluded from Git via `.gitignore`
- ✅ No sensitive data in source code
- ✅ Environment variable best practices

**Never commit your `.env` file or share your bot token publicly!**

## 🚀 Deployment

### Deployed on Railway

This bot is currently deployed on Railway for 24/7 uptime.

**Deploy your own:**

1. Fork this repository
2. Create account on [Railway](https://railway.app)
3. Create new project from GitHub repo
4. Add environment variable: `DISCORD_TOKEN`
5. Railway will auto-deploy!

**Start Command:**
```
python bot.py
```

## 🎯 Future Enhancements

- [ ] Add meme categories (animals, programming, gaming)
- [ ] Implement meme voting system
- [ ] Add cooldown/rate limiting
- [ ] Multiple meme sources
- [ ] Admin commands
- [ ] Database integration for statistics
- [ ] Custom prefix support

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is [MIT](LICENSE) licensed.

## 👤 Author

**Your Name**

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourprofile)

## 🌟 Show Your Support

Give a ⭐ if you like this project!

## 📚 What I Learned

Building this project helped me learn:

- **Discord Bot Development** - Using discord.py library and Discord API
- **Async/Await Programming** - Understanding asynchronous Python
- **REST API Integration** - Consuming external APIs
- **Environment Variables** - Secure credential management
- **Git & GitHub** - Version control and collaboration
- **Cloud Deployment** - Deploying applications to Railway
- **Slash Commands** - Implementing modern Discord interactions

## 🙏 Acknowledgments

- [discord.py](https://discordpy.readthedocs.io/) - Amazing Discord API wrapper
- [Meme API](https://meme-api.com) - Free meme source
- [Railway](https://railway.app) - Easy cloud deployment
- Discord community for support and inspiration

---

**Made with ❤️ and Python** | **Bringing laughs to Discord, one meme at a time** 🎭
