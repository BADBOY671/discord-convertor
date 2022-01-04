Hi 👋  <br>

Easy Anti Bad Word Pkg<br><br>

How To Install It In Your Project:?<br><br>
`
const convert = require('discord-convertor')
`
<br>
<br>
Basic Settings 🧢

<br><br>

```js
client.on('message', message => {
if(!message.guild) return 
const code = message.content.split(' ').slice(1).join(' ')
if(!code) return
convert.v12(code).then(v12code => {
message.author.send(`Your Code:${v12code} `)
})
})
```

<br>
<br>

Any Bug<br>

Contact With Me Discord: 
`
B A D B O Y #1502
`
<br>
<br>
<a href="https://www.npmjs.com/package/easy-anti-bad-word">Npm</a>
