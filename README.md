# robotframework-minecraftconsoleclientbindings

A resource library which provides an interface for controlling a Minecraft Console Clien
WebSocket bot

## Getting started

Beforehand note that this library only provides bindings/ for the Minecraft Console
Client WebSocket bot, it does not provide the functionality to connect to a minecraft
server on its own.

You will need to have Minecraft Console Client setup with the "Websocket" bot enabled.
[Installation](https://mccteam.github.io/guide/installation.html)
[Usage](https://mccteam.github.io/guide/usage.html)
It is recommended to first run MCC without config, so that the default config file gets
created where you can then set the server ip that you want, and enable the Websocket bot
(at the bottom of the config).

Install this module via pip: `pip install robotframework-minecraftconsoleclientbindings`

## Design

Provides RobotFramework Keywords for calling the underlying library mcc.py

## Useful links

Documentation that proved useful:
[https://websockets.readthedocs.io/en/stable/index.html](https://websockets.readthedocs.io/en/stable/index.html)
