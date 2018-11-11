# Markov_Bot

Generates messages in chats based on Markov chains.

# Container

I built a simple container around the bot so it's very simple to run it.
1. Pull the repository
2. Edit `markov_bot.py` in the `markov`-directory with your bot token and user agent.
3. Create the data-directory `mkdir -p /data/markov_bot` for saving the markov-chains outside of the container.
4. Then start with `docker-compose up -d`. The container builds automatically.
5. Have fun!