# Quick Links
- [Client Option](https://github.com/aiko-chan-ai/discord.js-selfbot-v13/blob/main/Document/ClientOption.md#client-settings)
- [Client Functions](https://github.com/aiko-chan-ai/discord.js-selfbot-v13/blob/main/Document/ClientOption.md#client-functions)

## Client Settings
```js
new Client({
  checkUpdate: true, // Check Package Update (Bot Ready) [Enable Default]
  readyStatus: false, // Set Custom Status sync from Account (Bot Ready) [Disable Default]
  autoCookie: true, //  Auto added Cookie and Fingerprint [Enable Default](https://github.com/aiko-chan-ai/discord.js-selfbot-v13/blob/main/DOCUMENT.md#http-options)
})
```

## Client Functions
- Update Cookie and Fingerprint
```js
client.updateCookie(): Promise<void>
```
- Reddem Nitro
```js
client.reddemNitro('code'): Promise<void>
```