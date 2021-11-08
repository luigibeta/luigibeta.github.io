---
title: "Command Spotlight - Pokémon Command"
excerpt: "A brief look at the Pokémon command on Luigi Beta"
date: 2020-02-17T02:00:00
author: "tee"
hidden: false
image: "https://cdn.discordapp.com/attachments/594950634755588126/679045005708492800/pokemon.png"
layout: post
---

Hello everyone, happy 2020! Today begins a blog series I call 'Command Spotlight': here I'll talk about some super cool commands on the bot! I'll try to do this weekly.

**Features**  
What better way to start than with the pokemon command? It does just what it sounds, you're able to view the entire Pokemon National Dex! Base stats, evolution information, and dex entries? They're all here! In addition to this information, you're also able to take a look at each Pokemon's various forms, such as Megas and regionals. You'll also be able to look at which modern games each Pokemon is available in in the future. I'm working on adding every single pokemon to the dex, and I've done 555 pokemon with more on the way at the time this post was created.

**Backend**  
This command works a little differently than the others: it uses two APIs. The first one is called PokeApi (you can search it up on Google and use it yourself!) It has pretty much all information for pokemon that you could ever want, but for my purposes, this simply isn't enough. It doesn't have any information on forms, pokedex entries, or evolution data. The pokemon names are even in lowercase! This is where my own, simpler API comes in. All the data that isn't present in the PokeApi is present in mine. Then the two APIs come together in the command, and BOOM; you have the command you see. This is also the reason why I can't just have only one API (at least for this command's purposes.) An image below shows what happens when I only use the PokeAPI and the other fields are left empty:  

![](https://cdn.discordapp.com/attachments/594950634755588126/679047408491036672/unknown.png)  

Glorious, right?  

Anyway, this concludes the first Command Spotlight. If you enjoyed it, <strike>like and subscribe</strike> consider sharing the bot with your friends, or this particular command too! I work really hard every day, so it would put a smile on my face to see people using it. Anyway, see you guys later!