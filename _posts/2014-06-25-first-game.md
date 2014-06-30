---
layout: default
---

#First Game "tower defence"

##background
* Apple launched a new language "Swift", and since I've been using Ruby, I thought now's the time to start iOS game development.
* I made a small app called "2d-tower-defence-Swift", and I'd like to share the code as well as __what makes a great game__.

##Code
* [2d-Tower-Defence-Swift](https://github.com/kenzan100/2dTowerDefence-Swift)
* screen shot ![tower defence screen shot](http://i.imgur.com/b1ly5ZQ.png)

##Game Elements
* It's a so-called "tower defence" game, which you are defending your 'valuables' while the enemy attackers are trying to invade.
* To see what it's like, one of easier ones you can play on PC is [Desktop Tower Defence](http://armorgames.com/play/1128/desktop-tower-defense-15) (it uses Flash).

###Game Pattern: Choice
* As well as many other good games, this game forces you to __choose__ one action over another.
* When you play the game(while enemies are reaching), you have [variables]({% post_url 2014-06-26-Variables-Game-Pattern %}) like your money in a game.
* Now the choice is, how you allocate this money.
* Typically, you have variety of 'units' that will attack enemies. Choosing one over others is a player's choice.
* Another easier option some of these games offer is [level]({% post_url 2014-06-30-Levels-Game-Pattern %}) up, which will improve (for example) your money increase rate.
* Depending on how well you allocate the [variables]({% post_url 2014-06-26-Variables-Game-Pattern %}) to those choices, your game result in [win or lose](#).

##Now It's your turn
* what's your idea on making a great 'tower defence' game?
* what are the other game elements which makes a great game of this kind?
* please leave comments on my [Twitter account](http://twitter.com/kenzan100)
