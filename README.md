# codespacemc

A fully containerized Minecraft server running on PaperMC server software for version 1.12.2, deployable in GitHub Codespaces with tunneling via Minekube.

## About

**codespacemc** is a complete Minecraft server setup designed to run in GitHub Codespaces, providing an easy way to host and manage a Minecraft server without requiring local infrastructure. The server runs PaperMC for Minecraft version 1.12.2 at a maximum allocation of 4GB of ram. This server is for thoes that want to play Minecraft with their friends but do not want to shell out some money for a paid hosting plan. This is not meant to be used to host a public multiplayer server, this was designed for multiplayer with friends.

**Project Lead:** Keith McKenzie  
**Email:** [keith@mckenzie.page](mailto:keith@mckenzie.page)  
**Website:** [https://mckenzie.page](https://mckenzie.page)  
**Project Page:** [https://mckenzie.page/codespacemc](https://mckenzie.page/codespacemc)

## Getting Started

### Prerequisites

- A GitHub account
- This guide

### Quick Start

1. **Fork this repository** to your own GitHub account, and ensure the repository is private*
2. **Create a Codespace** from your forked repository
3. **Wait for the Codespace to load** and for Node.js dependencies to install automatically
4. **Run the setup script:**
   ```bash
   bash ./setup.sh
   ```
5. **Follow the instructions on the terminal** to complete the setup process
6. **Start the server:**
   ```bash
   bash ./start.sh
   ```

## Running the Server

Once the setup is complete and you run the start script, the Minecraft server will launch. After it fully loads, you'll see the server's IP address in the terminal output. This address is provided by Minekube and allows you to connect to your server from any Minecraft client. The IP adress will look something like xxxxxxx.play.minekube.net.

Simply add the server address to your Minecraft server list and join!

Please note that you must leave the codespace open in your browser. If you close the page, the server will shut down. Please note that free personal GitHub accounts only get 120 hours of compute time per month.

To save your progress you can use /stop ingame to stop the server or run stop while the Minecraft server is running. After this you can commit changes and sync to main. 

*your repository should be public as Minecraft server logs log players IP addresses. 

## Credits

This project would not be possible without:

- **Mojang Studios** - for creating Minecraft
- **PaperMC Team** - for the server software
- **NEZNAMY** - for the TAB plugin
- **Minekube.net Team** - for the tunneling service 

## Support

For questions or issues, please visit the [project page](https://mckenzie.page/codespacemc) or contact Keith McKenzie at keith@mckenzie.page.

---

Happy mining!
