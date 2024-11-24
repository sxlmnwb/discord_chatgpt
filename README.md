## Run the bot with Docker

1. Build the Docker image & run the Docker container with `docker compose up -d`

2. Inspect whether the bot works well `docker logs -f chatgpt-discord-bot`

3. If want to start|stop|restart `docker compose <value> chatgpt-discord-bot`

4. For close logs `CTRL+C`

   ### Stop the bot:

   * `docker ps` to see the list of running services
   * `docker stop <BOT CONTAINER ID>` to stop the running bot

### Have a good chat!
