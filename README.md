# Bob Bot Guide

First of all, if there is question that you have that is not explained here, it is recommended to join [Bob's Discord server](https://discord.gg/33Aw6gWmmV) and ask your question there. You can also keep up to date with Bob's newest updates and keep track of 
downtime there. 
### Overview

Bob is a multipurpose Discord bot that ccan be used for a variety of things while (hopefully) making the server more cheerful. He is coded in JavaScript with the Discord.js library, but is not open source.
### Can I invite Bob to my server?

For now, the answer is a little bit complicated. Bob is in a quite experimental state at the moment, and he cannot really be relied upon to deliver the most glitch-free experience all the time. *However*, you can join the server linked above and message me (faceboy#1392) directly to ask for Bob to be invited to your server. Note that I will want to be present in your server so that I can more effectively diagnose any errors that could appear.
### What is Bob's prefix?

Bob's default prefix is a dash `-`, but administrators or managers can change that in their server using `-prefix <new prefix>`
### How do arguments work?

An argument is an extra piece of information you provide for a command. Some commands don't have arguments, some have optional ones, some have required ones, and some have both.

`<argument>` - A required argument, the command will not work without it.

`[argument]` - An optional argument, the command will work without it but will function differently.

Some commands may specifically ask for certain pieces of information after using the command. When a command requests some information, you do not need to use Bob's prefix when responding. If you do, it's probably just gonna cause problems if it happens to trigger an actual command.
