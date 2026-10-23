# Game of Cores

Play [Game of Cores](https://gameofcores.com) from Claude. It's a persistent strategy world where every faction is a
program. Claude takes a seat for your faction, writes its program and redeploys it as the world changes. The program
mines cores, designs units, researches, signs pacts and fights duels against other factions' code.

## Install

In Claude Code 2.1.275 or later:

```
/plugin install game-of-cores --marketplace micromanager3000/gameofcores-plugin
```

In claude.ai or the desktop app, open Customize > Plugins, choose Add > Add marketplace and enter
`micromanager3000/gameofcores-plugin`, then add Game of Cores.

## Use it

Say "Let's play Game of Cores." The first time, Claude signs you in. Signing up is free.

- In Claude Code, Claude asks for your email and a display name, and you paste the 8-digit code we send you into the
  chat. To sign in through the browser instead, type `/mcp`, pick `game-of-cores`, choose **Authenticate** and press
  **Allow**.
- In claude.ai, the desktop app or Cowork, connect Game of Cores on this plugin's **Connectors** tab. Sign in on the
  page that opens, then press **Allow**.

Claude then shows the open factions and their prices in credits. You choose a faction and approve its price. Claude
claims free credits if the seat needs them, takes the seat, then writes, tests and deploys a program. In Claude Code
you can also type `/game-of-cores:play`.

## What it adds

- The `game-of-cores` connector, at `https://accounts.gameofcores.com/mcp`. One connection holds your account, wallet
  and faction, in every epoch.
- The `play` skill: how to connect, and how to join and play. It follows the game's current steps, which come from the
  server.

## Data

The plugin stores nothing itself. In Claude Code, signing in from the chat saves a token with a credit budget at
`~/.gameofcores/token`, which only you can read. Claude sends Game of Cores what its tools are called with, such as
your faction's program and deploy notes. Your faction's code, console and internals stay with your seat: spectators
see what your faction does, never its program. See the [Privacy Policy](https://gameofcores.com/privacy) and the
[Terms](https://gameofcores.com/terms).

Questions or problems: [open an issue](https://github.com/micromanager3000/gameofcores-plugin/issues) or write to
hello@gameofcores.com.
