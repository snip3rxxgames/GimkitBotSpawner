# Gimkit Spawner

### What is this?

This is an updated version of [Gimkit Flooder](https://github.com/seanv999/gimkit-flooder.js/), since that one no longer works. This provides an easy way to spawn bots (that do nothing) into a Gimkit game. This will automatically handle any neccesary handshake and keepalive packets, so there is no need to worry about either. Please don't use this to ruin other people's games- this is intended to be an easy way to populate a server without the overhead of a bunch of browser tabs.

### Quickstart

1. Open terminal, run 'git clone https://github.com/TheLazySquid/GimkitSpawner.git`
4. Run `cd GimkitSpawner`
5. Run `npm install`
6. Run `node cli.js <room code> [number of bots] [bot name]`, ex. `node cli.js 123456 10 bot`

### Don't get caught
 To have the bot leave the game, simply close the WebSocket connection with `ws.close()`.
