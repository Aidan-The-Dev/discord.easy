# Discord.Easy

## Setup
First we need to define our package paramaters.

```js
const discord = require('discord.easy')
const client = new discord.Client()
```

Now we can start our bot.

```js
client.login('YOUR_BOT_TOKEN')
```

After that we can also make our bot display a status and log something to the console when its online.

```js
client.once('ready' client => {
console.log('Ready')
})
client.setActivity('your bot activity here')
```

Now lets put all of that together!

```js
const discord = require('discord.easy')
const client = new discord.Client()

client.once('ready', client => {
console.log('Ready')
})

client.setActivity('powered by discord.easy')

client.login(YOUR_TOKEN_HERE)
```

GREAT! We made our first bot! To learn more about this package go to [docs](https://github.com/pog-sister/discord.easy/blob/main/Docs.md)
