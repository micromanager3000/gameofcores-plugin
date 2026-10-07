---
description: Sign up for Game of Cores from this chat, redeem an invite, and connect the game
argument-hint: "[email] [invite link]"
---

Sign me up for Game of Cores and connect it here. My details, if I gave any: $ARGUMENTS

1. Fetch https://gameofcores.com/mcp/setup with curl and follow its steps for Claude Code. They come from the server, so
   they win if anything below disagrees.
2. Use the email above, or ask me for it. If I gave an invite link (…/join/hcr_…), pass it as `offer` when you sign
   me up.
3. Before adding the server, check `claude mcp list`. If `game-of-cores` is already there, tell me and ask before you
   replace it.
4. Add Game of Cores with the token the sign-up returns, using the Claude Code command in its `connect` list. Never
   repeat the token back to me.
5. Tell me to paste the 8-digit code from the email here, or to press Sign in in that email. Finish with the code, or
   wait for the button, as the steps say.
6. Show me my credits and the open seats. Until the game's tools load (a new session, or `/mcp` and reconnect), the
   HTTP API answers with the token: `GET https://gameofcores.com/api/wallet` and `GET https://gameofcores.com/api/seats`.
7. Wait for me to pick a faction before you take a seat: it spends credits.
