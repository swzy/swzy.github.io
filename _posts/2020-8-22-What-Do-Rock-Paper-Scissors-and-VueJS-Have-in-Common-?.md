---
title: "What Do Rock-Paper-Scissors and VueJS Have in Common?"
layout: post
date: 2020-8-22 11:57
headerImage: false
category: blog
author: Sam Yi
description: JavaScript, VueJS
---

Practiced using fetch API the other day as well as completed an evaluation on a IoT data company and now I am going to spend a day or so trying to write a common game, Rock-Paper-Scissors, using VueJS and Vue components. This will be an extension of sorts to the assignment given by TheOdinProject.

# 11:59

Setting up the project structure using VueCLI. I want there to be about four major components:
* The Start Menu
* The Player's Options
* The Computer's Options
* The Center Field/Battleground
* The Game

## The Start Menu

I want the Start Menu to essentially be an overlay page of sorts that will disappear once the 'Start Game' button is clicked. This page is also where game options will be selected and be passed down into the game itself as parameters. This page may have other miscellaneous information it.

## The Player's Options

The game flow will start only once the player makes their choice so my first impression is that the Player's option will be some very simple logic of taking the selected choice and passing it down to the 'battleground' component.

## The Computer's Options

Funny enough the Computer's options will likely have much more logic as I will have to have the computer randomly generate a move. But besides that, it will essentially replicate some of the logic involved in passing that choice down into the 'battleground' component as well.

## The Center Field/Battleground

This is where I can be the most creative. I designed for the Options components to pass their choices down to this one, and the logic for the comparison can be simple. However, I'm thinking I may practice with some animations or something...

## The Game

I only added this after writing out the different components, but it may be a better design to have a game component that holds on to the global game settings and keeps track of the wins. This likely means that the Game will first communicate with the Start Menu and then will receive data from The Center Field when rounds are decided. Kind of interesting to think about.

I haven't decided on the exact styling I want but I think it's important to focus more on the actual project structure and the component dynamics. Will update in a few hours.

*Totally did not update. But am making progress that I will record when I think it's substantial. There's alot to take in!*