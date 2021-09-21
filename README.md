# Discord-Chatbot

A self-learning chatbot for discord made with [Chatterbot](https://github.com/gunthercox/ChatterBot) and [Discord.py](https://github.com/Rapptz/discord.py)

## Running in container

Go to the project's directory then run

```bash
docker build -t discord_chatbot .
docker run -d --restart always --name aibot --env TOKEN=<BOT_TOKEN_HERE> --net=host discord_chatbot
```
To stop the bot:
```
docker stop aibot
docker rm aibot
```
