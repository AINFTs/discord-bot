<h1 align="center">Welcome to Discord Bot π</h1>

## Introduction

`Discord-Bot` μ κ°μ Έλ€κ° μνλ λΆλΆλ§ μμ ν΄μ Discord Botμ λ§λ€ μ μμ΅λλ€. Discord Bot API μ€ κ°μ₯ λ§μ΄ μ¬μ©νλ /command κΈ°λ₯κ³Ό /trigger κΈ°λ₯λ§ λ¨κ²¨ λμμ΅λλ€. ν΄λΉ λΆλΆμ κ°λ¨ν μμ ν΄μ μνλ Discord Botμ λ§λ€ μ μμ΅λλ€.

> An **open source** `discord.js` bot template which is based on official [discord.js guide](https://discordjs.guide/) to get started on making your very personal discord bot!

### Features:

#### β’ **Slash Command Handler:**

- Slash Command(/command)λ₯Ό μμ½κ² μμ ν΄μ λ§λ€ μ μμ΅λλ€.
- ./interactions/slash ν΄λ μλ slash command νμΌμ μΆκ°νκ³  [`CommandInteraction`](https://discord.js.org/#/docs/main/stable/class/CommandInteraction) objectλ₯Ό λ£λ μμΌλ‘ commandλ₯Ό μΆκ° ν  μ μμ΅λλ€ . μμΈν λ΄μ©μ μλ [documentation of discord.js](https://discord.js.org/#/docs/main/stable/class/CommandInteraction) λ₯Ό μ°Έκ³ ν΄ μ£ΌμΈμ.
- λμΆ© [setChannel.js](https://github.com/Laeyoung/discord-bot/blob/master/interactions/slash/setChannel.js) λ₯Ό λ³΅λΆν νμ λ°κΎΈλ μμΌλ‘ νλ©΄ λ©λλ€.  
- **μ€μ:** Discord Botμ 2κ°μ§ ννλ‘ λ±λ‘μ ν  μ μμ΅λλ€. λ΄κ° μ§μ ν Discord Server (κ°λ°λ¬Έμμμλ GuildλΌλ μ©μ΄λ₯Ό μ¬μ©)λ§ μ¬μ©νκ² νλ κ²κ³Ό Global νκ² λͺ¨λ  Serverμμ μ¬μ©νκ² νλ λ°©λ², 2κ°μ§κ° μμ΅λλ€. μ μλ λ΄κ° μ€μ ν μλ²μμλ§ μ¬μ© ν  μ μκ³ , μλ‘ μμ±ν Slash Commandκ° λ°λ‘ λ°μμ΄ λ©λλ€. νμλ λ°μμ΄ λλλ° μ΅λ 1μκ°κΉμ§ κ±Έλ¦΄ μ μμ΅λλ€.

#### β’ **Trigger Handler:**

- Triggerλ μ μ κ° `νΉμ  μ±λ`μ λ³΄λΈ λ³΄λΈ λ©μΈμ§μ `νΉμ  λ¬Έκ΅¬`κ° μμ λ, λμμ ν©λλ€.
- μ±λμ μ€μ μ ν΄μΌνλ©°, `/set-channel` λͺλ Ήμ΄λ₯Ό μ΄μ©ν΄ μ€μ  ν  μ μμ΅λλ€.
- κΈ°λ³Έ μ€μ μ μλμ κ°μ΄ μ€μ  λμ΄ μμ΅λλ€.
  - keywords: `ainft`
  - prefixes: `yeoreum`
  - suffixes: `?`
- μλ₯Ό λ€μ΄, `?`λ‘ λλλ λ¬Έμ₯μ Triggerκ° λ©λλ€.
- μμΈν λ΄μ©μ λ€μ νμΌμ μ°Έκ³ ν΄λ³΄μΈμ, [`chatbot.js`](https://github.com/Laeyoung/discord-bot/blob/master/triggers/chatbot.js).

## Requirements

Node.js 16+

## Install

```sh
npm install
```

## Envs

- rename [`sample.env`](https://github.com/NamVr/DiscordBot-Template/blob/master/sample.env) to `.env` and fill the token and other values.

## Run

### for production
```sh
npm start
```

### for develop
```sh
npm run dev
```


## π Acknowledgments

This project is based on [DiscordBot-Template](https://github.com/NamVr/DiscordBot-Template) by [Naman Vrati](https://github.com/NamVr)

---
