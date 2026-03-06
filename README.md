# 🐱 HAJIMI 哈基米 — The Cutest Cat on Solana

<div align="center">

![Hajimi Banner](hajimi_banner.jpg)

**$HAJIMI** — Pumpfun上最火爆的猫咪 🔥

[Website](https://hajimisolana.xyz) · [Twitter](https://x.com/hajimisolana) · [TikTok](https://tiktok.com/@metroichetnhe12334) · [Community](https://x.com/i/communities/2029915015441219603)

**Contract Address:**
```
79e2P2GxExotT5jtUNNs3Nyp9YzRk28WTJYXHr4ypump
```

</div>

---

## What is Hajimi? 哈基米是什么？

Hajimi (哈基米) is the viral kawaii Chinese cat taking over Solana. Born from internet culture, powered by community, and now living on the blockchain.

- 🐾 **Community Takeover (CTO)** — fully community-owned
- 🤖 **AI-Powered** — DeepSeek chatbot, AI meme generator
- 🌏 **Bilingual** — Chinese + English community
- 📱 **TikTok Viral** — millions of views across Douyin & TikTok

## Features 功能

### 🐱 Hajimi AI Chatbot
Talk to Hajimi directly on the website. Powered by [DeepSeek](https://deepseek.com) AI, the chatbot responds in character as the kawaii cat — in Chinese and English.

- Full personality system with kawaii cat behavior
- Knows about $HAJIMI, Solana, crypto culture
- Bilingual support (中文 / English)
- Conversation memory within session

### 🎨 Meme Generator
Two modes for creating Hajimi memes:

**Free Editor** — No account needed
- Hajimi image as base with customizable text
- 8 styles: Original, Pink, Dark, Laser Eyes, Diamond Hands, Moon, Hearts, Fire
- 4 text colors, instant download as PNG

**AI Generator** — Powered by DALL-E 3
- Describe any scene and AI generates it
- 6 preset prompts for quick memes
- Gallery saves all generated memes

### 🤖 Twitter Bot (X)
Automated kawaii Chinese cat Twitter account with:
- 30+ pre-written time-aware tweets in Chinese
- Optional AI-generated tweets via OpenAI
- Manual tweet and video posting via CLI
- Auto-tweet scheduling with configurable intervals
- Reply functionality

## Tech Stack 技术栈

| Component | Technology |
|-----------|-----------|
| Website | Vanilla HTML/CSS/JS |
| Chatbot | DeepSeek API (deepseek-chat) |
| Meme AI | OpenAI DALL-E 3 |
| Twitter Bot | Python + Tweepy |
| Hosting | Netlify |
| Domain | Porkbun |

## Project Structure 项目结构

```
hajimi/
├── index.html          # Main website
├── hajimi.jpg          # Cat icon
├── hajimi_banner.jpg   # Banner image
└── kawaii-cat-bot/
    ├── bot.py          # Twitter bot
    ├── .env.example    # Config template
    └── requirements.txt
```

## Running the Twitter Bot

```bash
cd kawaii-cat-bot
pip install -r requirements.txt
cp .env.example .env
# Add your X API keys to .env
python bot.py
```

### Bot Commands
| Command | Description |
|---------|------------|
| `tweet <text>` | Post a tweet |
| `video <file> <text>` | Tweet with image/video |
| `auto` | Trigger auto-tweet |
| `generate` | Preview generated tweet |
| `reply <id> <text>` | Reply to a tweet |
| `interval <min>` | Change auto-tweet timing |
| `pause` / `resume` | Toggle auto-tweeting |

## Community 社区

Join the Hajimi family:
- 🐦 **Twitter:** [@hajimisolana](https://x.com/hajimisolana)
- 🎵 **TikTok:** [@metroichetnhe12334](https://tiktok.com/@metroichetnhe12334)
- 👥 **X Community:** [Join here](https://x.com/i/communities/2029915015441219603)

## Contributing

Hajimi is community-owned. PRs welcome for:
- New meme templates and styles
- Chatbot personality improvements
- Website features and translations
- Bot enhancements

## License

MIT — Built with 💕 by the Hajimi community

---

<div align="center">

「做一只快乐的猫就够了喵～」

**(=^・ω・^=) 💕**

</div>
