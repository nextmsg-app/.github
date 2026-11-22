## NextMsg

**The one-way messenger for AI agents, scripts and servers.** Send a push to your phone with one HTTP request. No bots, no chat apps, no account.

```sh
curl -d 'Deploy finished' https://api.nextmsg.app/p/$NEXTMSG_KEY
```

- 🤖 **MCP server:** [`@nextmsg/mcp`](https://github.com/nextmsg-app/mcp) gives Claude, Cursor, Codex, Antigravity and other agents a `notify_human` tool ([npm](https://www.npmjs.com/package/@nextmsg/mcp))
- 🏠 **Home Assistant:** [NextMsg integration](https://github.com/nextmsg-app/home-assistant) for HACS: set up with a code from the app, one notify entity per channel
- ⚙️ **GitHub Action:** [NextMsg Notify](https://github.com/marketplace/actions/nextmsg-notify) on the Marketplace: `uses: nextmsg-app/notify-action@v1`
- 📚 **Guides:** [GitHub Actions](https://nextmsg.app/guides/github-actions), [cron jobs](https://nextmsg.app/guides/cron-jobs), [servers](https://nextmsg.app/guides/server-alerts), [AWS](https://nextmsg.app/guides/aws), [Claude Code](https://nextmsg.app/guides/claude-code), [Cursor](https://nextmsg.app/guides/cursor), [Codex](https://nextmsg.app/guides/codex), [Antigravity](https://nextmsg.app/guides/antigravity), [Home Assistant](https://nextmsg.app/guides/home-assistant), [Healthchecks.io](https://nextmsg.app/guides/healthchecks), [Phare](https://nextmsg.app/guides/phare)
- 📱 **Apps:** [App Store](https://apps.apple.com/app/nextmsg-push-notifications/id6831546010) (iPhone) and [Google Play](https://play.google.com/store/apps/details?id=app.nextmsg) (Android). Free for 100 messages a month; Pro is a one-time purchase.
- 🔗 [nextmsg.app](https://nextmsg.app) · [llms.txt](https://nextmsg.app/llms.txt) · [API spec](https://api.nextmsg.app/openapi.json) · [hello@nextmsg.app](mailto:hello@nextmsg.app)
