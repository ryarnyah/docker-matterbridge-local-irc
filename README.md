# Docker MatterBridge IRCd local container

Used to run à local IRCd container to bridge it to mattermost with matterbridge.

## To run it
```bash
cp matterbridge.toml.sample matterbridge.toml
docker-compose up -d
```
Now you can connect to localhost:6667 with erc per example :D
