# Erela.js-filters

A plugin for erela.js to support native lavalink filters.

# Install Package

To Install this package, type the following into your project's terminal:

`npm install chris8889/erela.js-filters`

# Filters

• `bass`
• `bassboost`
• `bassboosthigh`
• `classical`
• `eightd`
• `electronic`
• `errape`
• `gaming`
• `highfull`
• `highvoice`
• `karaoke`
• `nightcore`
• `party`
• `pop`
• `radio`
• `rock`
• `soft`
• `treblebass`
• `tremolo`
• `vaporewave`
• `vibrato`

# Example Code

```js
const {Manager} = require(`erela.js`);
const {FilterManager} = require(`erela.js-custom-filters`);

const manager = new Manager({
    plugins: [
        new FilterManager()
    ]
});

// Your code goes here
// In your filter command

<Player>.karaok = true;
<Player>.karaok = false;
```

# Need Help? Join Our Discord Server!

https://discord.gg/4j8s8gnV7A