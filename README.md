If you didn't previously know about Bob Bot and were sent here to learn about him (I don't care if Bob is inanimate, I worked hard on him so I'm gonna call him by whatever pronoun I want), then let me teach you a couple things.

-----[ Overview ]-----

Basically, Bob is a Discord bot that is built to do a large variety of things while (hopefully) making servers a little extra cheerful. I'm developing him as just an interesting ongoing project that helps me improve my skills. He does not need any premium version, and all the features he has are unlocked by default.

Bob has an official Discord server where you can ask any questions, get any help, suggest any features or provide any feedback. You do not have to join, but it would be quite helpful for the development process.

At the moment, Bob's invite link is not public. Bob is in a quite experimental state and needs some more development before I can let him go in the wild. However, you can request an invite link from me directly. You can join Bob's Discord server and ask me (faceboy#1392) for the link. Just note that I do want to be present in your server to observe how Bob is being used, to provide assistance, and to investigate in case I get any unexpected errors.

Bob is coded in JavaScript with the Discord.js library, and is currently hosted on my own PC. Note that this means there may be some periods of downtime, though I do intend to get a proper hosting service at some point. Luckily, my PC is fairly powerful and I keep it turned on a lot.

Bob is not open source, just because Im too lazy to commit every change, lol. Plus, my code does not set a very good example for others.

-----[ Basic Usage ]-----

<Prefix>

First of all, Bob's default prefix is a dash "-", however you can set your own custom prefix in a server using the command "-prefix <new prefix>"
You can also @ Bob at the beginning of a message as a prefix in case you ever forget what prefix is set.

<Arguments>

A lot of commands have "arguments", which are extra pieces of information that you provide when you use a command.
You can see what arguments (if any) a command needs by typing "-help <command name>" <- That right there is an argument.

Argument names surrounded in angle brackets <> signify that the argument is required, and the command cannot function without it.
Argument names surrounded in square brackets [] mean that the argument is optional for that command, and can be ommited. This will change what the command outputs.

<Basic commands>

The -help command has a number of uses. The basic usage of it is "-help ["categories"/category name/command name]", which may be a bit long but it can help you learn about any command. I recommend using it to learn about any command you may have questions about, including the ones below.

"-prefix" sets a server prefix.

"-nickname" sets Bob's nickname in a server. You cannot just change his nickname manually, as he will revert it every time he is reset (which is often). Using this command changes that.

"-set" lets you modify several settings, but is a very work-in-progress command.

"-ping" lets you see Bob's current ping, or how good of a connection he has. The roundtrip latency is the important bit, as it signifies how long it takes for Bob to send a message and then receive back confirmation that he has sent it.

"-uptime" lets you see Bob's current uptime, or how long it has been since the last reset.

"-kick", "-ban", and "-purge" are useful moderation commands.

"-permissions" lets you see the permissions of yourself or any other user in any particular channel.

"-cat" sends a random cute cate image. That's all. You're welcome.
