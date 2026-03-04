# hi, i play guitar and dj sometimes 🎸

Builder of AI tools, bots, and small web products.  
Currently building **Leaderbot** — a Messenger AI bot running on Fly.io.

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Fly.io](https://img.shields.io/badge/Fly.io-8B5CF6?logo=flydotio&logoColor=white)
![OpenAI API](https://img.shields.io/badge/OpenAI_API-412991?logo=openai&logoColor=white)
![Messenger API](https://img.shields.io/badge/Messenger_API-0084FF?logo=messenger&logoColor=white)

## Projects

### [Leaderbot](https://github.com/Dj-Shortcut/Leaderbot)
Messenger AI bot with OpenAI image generation.

**Tech:** Node.js · Redis · Fly.io · OpenAI

**Features:**
- stateless deployment
- Redis-backed quota system
- webhook signature verification
- async image generation

### [thesenerbarber.shop](https://thesenerbarber.shop)
Landing page built and deployed for a real client.

## Architecture

```text
Messenger
  ↓
Meta webhook
  ↓
Fly.io server
  ↓
Redis (state + quotas)
  ↓
OpenAI API
```
