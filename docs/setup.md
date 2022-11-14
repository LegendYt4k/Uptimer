# ✍ Guides

### Setting up Slash Commands

- Slash commands are disabled by default
- In the **settings.js** set **SLASH_GLOBLE = true**  This will ensure that all the commands are registered globally immediately

{% hint style="warning" %}
_**Global slash commands** can take upto 1 hour to be shown across all guilds_
{% endhint %}

### Setting up Dashboard

- In the config.json under the dashboard folder , make sure you fill in all the requirements to make your dashboard go live.
- Add your baseURL in Url, `http://localhost:8080/api/callback` in your application OAuth2 redirects page in the [discord developer portal](https://discord.com/developers/applications)

```
: {
    CLIENT_ID: "", // your bots client id
    SECRET: "", // your bots secret
    URL: "http://localhost:8080", //  url
    port: "8080", // port to run the bot on
  },
```


