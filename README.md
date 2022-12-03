# minecraftDockerServerGUI
A GUI built to intuitively create and manage Bedrock Minecraft Servers

Purpose: Create an easy to download and use GUI application that can create and manage bedrock [maybe add java later?] Minecraft servers. It should be operable by a non-technical user, with desired features and as much management cabailities as a person with command line access and knowledge would have.

Repo trello Board: https://trello.com/b/UPQvh09S/todo

Base management software: https://github.com/itzg/docker-minecraft-bedrock-server

## Desired features:
- Create a new server
- Start and stop server
- Edit server configurations
- Edit server whitelist
- Edit server blacklist
- Backup server at specified intervals (either time-based, or player-enterance based)
- Have microsoft sign-in?
  + Access to account friends list
  + use for necessary access controls
  + easier account-based whitelisting/role assignment
  + will likely have to use REST endpoints instead of API, as API is in C++?
- retrieve the server worldsave to a given dir
- set the server world save from a given dir


## Techstack
- Java (What version?) (Use Java FX?)
- Docker/Docker compose
- GitHub for version control
- draw.io for GUI design/flowcharts

