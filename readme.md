# Arras Mayhem
The offical client for the Arrasio5 server.
Image of Yaktocat](https://media.discordapp.net/attachments/738824642441117716/744373628942024714/w7S7hI5.png)
# Features
- Sound effects!
- Music!
- Lightweight, separate client! 
- More colours!
- Fixed hotkeys! (Be sure your server project has them binded)
- Deployment to Repl.it or Heroku! Still works with Glitch!
- Webserver compatibility with 5 different languages!

# Webservers
The client is able to be hosted as either a Node.js Express, PHP, Go HTTP, Ruby Webrick or Python Flask webserver. Details below! Examples are linked as well.

- NodeJS Express server:
   ``node index.js``
    - <https://repl.it/@umineko/arras-express> 
    - <https://gitlab.com/seaguli/arras-express>
- PHP server:
   ``heroku-php-apache2`` **HEROKU ONLY, no script req'd for repl.it**
   - <https://repl.it/@umineko/arras-php>
- Python Flask server:
   ``python main.py`` 
   - <https://repl.it/@umineko/arras-flask>
   - <https://gitlab.com/seaguli/arras-flask>
- Go HTTP server:
   ``go build`` 
   - <https://repl.it/@umineko/arras-go>
   - <https://gitlab.com/seaguli/arras-go>
- Ruby Webrick server:
   ``ruby main.rb`` 
   - <https://repl.it/@umineko/arras-ruby>
   - <https://gitlab.com/seaguli/arras-ruby>
   
Additonal code is available on my Github project's page, <https://github.com/seaguli/arras-mayhem>
# Remixing
Feel free to remix this project and modify it to your own liking!

<sub><sup>
    ask me if you want any aspect of the server's code
</sub></sup>
# Setting it up
The client currently uses arrasio5 as a server, but you can edit it!
- Go to line ~3241 in bundle.js and edit the code. It should look like this:

                 -   id: "a",
                 -   type: "4TDM",
                 -  code: "arras",
                 -  at: p.glitch ("YOUR-ARRAS-SERVER")
                 
- p.glitch is the name of your Arras.io server hosted on Glitch.com. For example, ("arrasio5")
- It also works with servers hosted on Heroku, simply change `p.glitch` to `p.heroku` and fill in your server normally.
- Type is the gamemode of your server. For example, "4TDM" for 4 Team Deathmatch, "FFA" for Free For All.
- Code isn't important

# Credits
- Original Client by ProKameron
<https://glitch.com/~imp-template2>
- Seaguli
- Various StackOverflow contributors (For webserver code)
