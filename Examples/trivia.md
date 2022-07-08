# SIMPLE WAY
```js
const { Trivia } = require("discord.js-trivia")
new Trivia({
    message: message,
    slash_command: false,
}).newTrivia();
```

# SIMPLE WAY WITH SLASH COMMANDS
```js
const { Trivia } = require("discord.js-trivia")
new Trivia({
    message: interaction,
    slash_command: true,
}).newTrivia();
```

# ADVANCE WAY
```js
new Trivia({
      message: message,
      slash_command: false,
      difficulty: "easy",
      time: 60000,
      configMessage: {
           winMessage: "Congrats, The answer was {answer}",
           loseMessage: "Wrong!, The correct answer was {answer}",
           timeoutMessage: "You didnt asnwer in time, the answer was {answer}"
            },
       embed: {
            title: 'Trivia',
            color: '#5865F2'
            }
   }).newTrivia();
```

# ADVANCE WAY WITH SLASH COMMANDS
```js
new Trivia({
      message: interaction,
      slash_command: true,
      difficulty: "easy",
      time: 60000,
      configMessage: {
           winMessage: "Congrats, The answer was {answer}",
           loseMessage: "Wrong!, The correct answer was {answer}",
           timeoutMessage: "You didnt asnwer in time, the answer was {answer}"
            },
       embed: {
            title: 'Trivia',
            color: '#5865F2'
            }
   }).newTrivia();
```
