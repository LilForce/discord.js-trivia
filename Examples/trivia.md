# SIMPLE WAY
```js
const Trivia = require("discord.js-trivia")
new Trivia({
    message: message,
    slash_command: false,
}).newTrivia();
```

# SIMPLE WAY WITH SLASH COMMANDS
```js
const Trivia = require("discord.js-trivia")
new Trivia({
    message: interaction,
    slash_command: true,
}).newTrivia();
```

# ADVANCE WAY
```js
const Trivia = require("discord.js-trivia")
new Trivia({
    message: message,
    slash_command: false,
    difficulty: "easy", //easy medium or hard
    embed: {
        title: 'Trivia', 
        color: '#5865F2'
    }
}).newTrivia();
```

# ADVANCE WAY WITH SLASH COMMANDS
```js
const Trivia = require("discord.js-trivia")
new Trivia({
    message: interaction,
    slash_command: true,
    difficulty: "easy", //easy medium or hard
    embed: {
        title: 'Trivia', 
        color: '#5865F2'
    }
}).newTrivia();
```
