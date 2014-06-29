---
layout: default
---

#"Mega Jump" game analysis

##What is "Mega Jump"?
* It's a game where a character __keeps moving upward(y-axis) direction by collecting stars__, while gravity towards opposite direction keeps pulling a character to the ground. ![mega jump game pattern screen shot](http://getsetgames.com/wp-content/uploads/2010/12/mega-jump-android-screen-web-001.jpg)
* As long as you can keep collecting stars to bounce him up, you'll keep scoring.
* As seen in the screen shot above, __there are "boosts" you can collect to empower players__ for exciting actions.

##Analysis of the game
* When you look at the game components, __it's incredibly few:__ it's got a moving player character, as well as stars(scoring objects), and obstacles you should avoid hitting.
* It uses its physics engine wisely, by limiting the player's eye into one (y-axis) direction.
* If you keep hitting the stars, it'll accelerate its velocity toward moving direction, resulting straightforward __"Catharsis"__(described in [this pattern]({% post_url 2014-06-28-Stress-and-Catharsis-Game-Pattern %})).
* Also it's so __easy to fail__ this upward moving combo. Just one wrong iPhone tilt would kill the character, resetting all stage points.
* This __instant excitement and stress in "[Stress and Catharsis]({% post_url 2014-06-28-Stress-and-Catharsis-Game-Pattern %})"__ is what makes this game addictive.
* Because it's easy to restart and you can [compare](#) to see whether you have beat previous try, the game makes a player want to try again and again.

##Issue
* While this simple game is very pleasing to play, it's essentaially __"beat the level" type__ of game.
* So when a player thinks "I've done all the techniques this game requries", a player will quit playing this game.
* That's the reason it has many "powerups", "boosts", trying to make players think it has whole lot more aspects to play.

##Making the game live longer
* This is a harder issue to solve, since it's pretty much __the game core logic a player thinks he's played enough__.
* So you could say "the game has lived long enough, it's time to make other 'spinouts' using the same character".
* Another try might be adding __"real person interaction"__, such as introducing battle feature to the game.
* This one is though something you should be careful of, because __a player is really sensitive on level match system__.
* If another player's level is too high to compete, a player loses his motivation to compete. Providing a good match depends on player community size, which often is uncontrollable variable.
* So, it should be more of __"searching an answer from maniac players" question__.
  * __Try looking for reasons why some players won't just quit playing__, why they keep enjoying every tiny aspects of the game.
  * And __try to estimate what level or skill a player has to have__ in order to enjoy the game with that extent.
  * Once you find out some of popular maniac way to enjoy the game, then you can __add extra tutorial or extra game mode focused for that game play__.
