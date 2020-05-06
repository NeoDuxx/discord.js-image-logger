
This will be an extremely basic example of how to setup the module.

// First we require the Discord.js library.
const Discord = require("discord.js");

// Now we require the module.
const DIL = require("discord.js-image-logger");

// Start a new Discord Client.
const client = new Discord.Client();
// Start the module with some custom options.
DIL(client, {
  method: "embed", // can be "embed" "link" or "image"
  logChannel: "images",
  channels: ["some-channel","453502285318848512","another-channel"]
})

// Login the Client
client.login(process.env.BOT_TOKEN);
