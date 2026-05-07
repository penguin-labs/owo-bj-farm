<div align="center">
  
  <div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=FF9ACD&center=true&vCenter=true&width=500&height=60&lines=🐧+owo+blackjack+farm;.play+%7C+cute+%7C+profit" alt="Typing Animation" />
</div>
  <img src="https://cdn.discordapp.com/emojis/861110080350453770.gif" width="80" />
  
  # 🃏 owo blackjack farm
  
  **automated blackjack for the owo bot**
  
  *because grinding manually is for penguins without flippers*
  
  [![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
  [![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com)
  [![License](https://img.shields.io/badge/License-MIT-FF9ACD?style=for-the-badge)](LICENSE)
  
  ⚠️ *use responsibly — this is for educational purposes* ⚠️
  Leave a star to support the developer.
  
</div>

---

## 🎀 what is this?

owo blackjack farm is a **cute little automation script** that plays blackjack in the [OwO bot](https://top.gg/bot/408785106942164992) on Discord.

it:
- 🃏 automatically joins blackjack games
- 🧠 plays using basic strategy (hit on 16 or less)
- 💰 farms cowoncy (the in-game currency)
- 🐧 looks adorable while doing it

think of it as your **personal gambling penguin**.

---

## 🎮 how it works

```mermaid
flowchart LR
    A[Discord Channel] -->|watches messages| B[Bot]
    B -->|sees blackjack game| C[Auto-join]
    C -->|detects your cards| D[Decision Engine]
    D -->|hit or stand| E[Send Command]
    E -->|repeat| A
    
    style A fill:#5865F2,stroke:#FF9ACD,color:#fff
    style B fill:#FF9ACD,stroke:#5865F2,color:#fff
    style C fill:#5865F2,stroke:#FF9ACD,color:#fff
    style D fill:#FF9ACD,stroke:#5865F2,color:#fff
    style E fill:#5865F2,stroke:#FF9ACD,color:#fff
