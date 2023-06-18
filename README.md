

[Discord
](https://raw.githubusercontent.com/Delaford/game/master/src/assets/github/logo.png)

Let me know your interest on the GitHub discussions thread!

Welcome to Delaford. An online, 2D medieval game using JavaScript and HTML5. Game screenshot

https://github.com/delaford/game/blob/master/src/assets/github/readme_hero.png

Getting Started
First, fork the repository. Then, go into your favorite terminal.

git clone git@github.com:YOUR_USERNAME/game.git
cd game
npm install
npm run serve
npm run serve will start the development server and watch for changes on the client-side code inside the src folder and otherwise elsewhere applicable.

Now, while still inside the game folder, open another terminal session in that same location. Type and run npm run dev:node. This will start the Node.js game server.

If you want to debug, type npm run ndb. ndb is Google Chrome's Node Debugging tool which allows Node.js programs to be easily debugged and see all its context and variables. Highly recommended for a much easier time.

Now you may visit http://localhost:8080 to login and start developing!

For a better time, make sure to join the Discord channel to talk to other developers for help and exclusive dicussions!

Please be aware of a possible scam in regards to Delaford that promises money for testing or similar action.

Contributing
Please check out our CONTRIBUTING.md guide on how you can actively participate in the development of this medieval game. It's pretty easy and fun!

Systems and Engines
Here are the types of things I will be adding as a minimum viable product (alpha). Not too over the top but enough to cover the basics until more is added. Each section links to a project which will contain its sub-tasks within.

What does a checkmark mean?
When an item is checkmarked, it means the basic foundation is in place but not necessarily complete. For example, Inventory is checkmarked but it currently only supports weapons. You can help fix that.

Player
 Walking / pathfinding
 Context-menu / Actions
 Health and stats
 Inventory
 Character wear
 Your first quest
User Interface
 Inventory tab
 Quests tab
 Chatbox (for players and actions)
 Character wear tab
 Overall look & feel
NPC
 Trading (Shops)
 Dialog Interaction
 Walking around
 Banking
Monsters
 Battle System
 Looting
 Spawning
Networking
 Players see each other
 Non-playable characters
 Monsters
 Player trading
 Items
World
 Respawn system
 Player versus Player
 Resource skills
 Mining
 Smithing (Almost finished)
 Fishing
 Cooking
Once all of these items are checked, Delaford will be stable without breaking changes. But for the time being, please jump in and help add some of these features -- if you'd like!

Debugging
Learning how to debug in this game is critical in order to interact with the Node.js server and to the client. Your primary source should be the ndb tool from Google. It is an improved debugging experience witch drastically improved client-side debugging.

Read more at DEBUGGING.md.

Notice
Delaford contains work from multiple sources not organically made by contributions from Delaford directly.

Tileset, monsters, items, players by David E. Gervais. · CC license
Main screen music by Matthew Pablo. · CC license
Game font 'PixelMix' by Andrew Tyler
Chat font 'IBM VGA 8' by IBM.
Heroicons by Steve Schoger
Website Status
Website is not currently up. The number of users did not justify the monthly charge.

Possible Scam Notice
Delaford contributors nor anyone associated with Delaford will never contact you in regards testing or instructing you to downloading anything in regards to the development of the game for the reward of payment or digital currency such as cryptocurrency.

We have had verifiable reports of users pretending to be owners of Delaford promising money if they download a folder with the repository's contents inside. Please be aware.
