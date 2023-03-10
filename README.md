# craft-discord-app

![usage](https://b.top4top.io/p_25878jq601.png)

![version](https://img.shields.io/npm/v/craft-discord-app)
![version](https://img.shields.io/bundlephobia/min/craft-discord-app?label=min)

A CLI tool allows you to get your Discord bot project up and running much faster and easier than copying and pasting boilerplate code from previous projects. It offers a modern setup with zero configuration!

## Quick Start

First, check that you have the most recent LTS version of [NodeJS](https://nodejs.org/en/) installed on your machine, and you should be go to go. Install `craft-discord-app` globally on your machine so you can use it anywhere.

```
npm i -g craft-discord-app
```

Then `cd` to the location where you want to create your project and launch the tool via

```
npx craft-discord-app
```

![usage](https://cdn.discordapp.com/attachments/992369500206936196/1070112489326526494/tdasghadsgh.gif)

## Developement Process

You need to be familiar with Typescript because all templates generated by this tool are in Typescript. If you are still using JavaScript, you should be aware that you have ongoing problems 😁.
|scripts| description |
|--|--|
|`dev` | uses `ts-node` to JIT transforms your Typescript bot files to Javascript and run it using NodeJS|
|`build` | transpile all files to `dist` folder for production|
|`start` | launches your bot in production environments |

## Contributing

I would love to see people contribute to this project and fix the mistakes I have made.

#

> **NOTE ⚠** <br/>
> This tool is not officially from [Discord](https://discord.com/) or even [DiscordJS](https://discordjs.dev/)
