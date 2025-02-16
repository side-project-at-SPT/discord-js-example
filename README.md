1. 註冊 Discord Application https://discord.com/developers/applications
2. 邀請機器人至伺服器
3. 新增 config.json 檔案
4. 安裝依賴 `pnpm i` (目前版本使用 node.js v20.14.0 以及 pnpm v9.15.2)
5. 執行 `pnpm start` 並觀察結果
6. 至 Discord 伺服器輸入 `/ping` 以及其他指令測試

## config.json

```json
{
  "token": "YOUR-DISCORD-APPLICATION-TOKEN",
  "clientId": "YOUR-DISCORD-APPLICATION-ID",
  "guildId": "YOUR-DISCORD-GUILD-ID (aka server id)"
}
```

## Docs

- [discord.js](https://discordjs.guide/)
