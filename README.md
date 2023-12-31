# Project Description

This project is a WhatsApp bot that uses OpenAI's ChatGPT (GPT-4) to respond to user inputs.

![photo_2023-01-06 20 06 27](https://user-images.githubusercontent.com/38583057/211094028-9c512d9c-56df-4195-b21b-f588a33a7d79.jpeg)

## Requirements

- Node.js (18.x)
- A recent version of npm
- An OpenAI Account
- A Whatsapp Account

## Usage

The bot will now respond to all messages you receive.

To use the bot in group chats, simply mention the bot's name or any of the prefixes listed below in your message.

```
  "gpt",
  "GPT",
  "gpt3",
  "GPT3",
  "gpt-3",
  "GPT-3",
  "bot",
  "Bot",
  "BOT",
```

To change the prefixes, update the array located inside `src/configs/constants.ts`

## Example

`What is the meaning of life?`
<br/>
`bot What is the meaning of life?`

The bot only responds to messages that are received by you, not sent. It will also work with group messages.
The bot will respond to all private messages you receive and only messages taht contain any of the prefixes in group chats.
To change the OpenAI model being used, update the `OPENAI_MODEL` variable in the `config/constants.ts` file.
