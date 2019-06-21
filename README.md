# Squishables_Public
<img src="https://drive.google.com/uc?export=download&id=1nce6WdfeBdENbUeXkrklkHDqsAeati7g/view?usp=sharing" width="850px"/>
<br>
Squishable is a Context-Based 2D platformer where you control your character’s velocity, acceleration, and impulse/jerk vector with the same 4 keys. It was primarily designed to be a couch coop game.
<br>
This is some of the progress I was able to make over a 6 to 9 month period. Implementing all the desired mechanics turned out to be very difficult and I realized that I was going to have to recreate the base of the game. Unfortunately by then I had run out time. Hopefully one day I can finish it.
<br>
But for now this will hold the progress I am willing to show and the lessons I learned along the way.
<br>
<br>
<a href="https://drive.google.com/file/d/14L2p0aEoZXu6D6cgJic6okR7UKYMq-GV/view?usp=sharing">Video Link Of Tutorial/Ready Screen</a>
<br>
I tried to do way to many things here. I was hoping that since players have to spend a fair ammount of time getting ready for the game I could use this time to remind players of some of the mechanics since there are so many. Some things worked, some didn't.
<br>
I was hoping to remind the player that
<ol>
  <li>without slime (a.k.a. health) they will overheat and explode (a.k.a. die)</li>
  <li>they can gather slime (a.k.a. health)</li>
  <li>they can gather the slime of other players (expressed by the very bad color mixing mechanic)</li>
  <li>the slime tail indicates the direction of the players movement</li>
  <li>the eye (and more obviously the arrow) indicates the interpreted force vector</li>
  <li>double tapping in any direction makes you lose some health but also pushes you forward faster (I forgot to show this but its how each player readys up)</li>
</ol>
But trying to communicate the 1st, 2nd, and 3rd just made the ready up process slow and tedious.
<br>
<br>
<a href="https://drive.google.com/file/d/1nuBLRlomhLP8-J8zDp2tBDWbLVA6XTNO/view?usp=sharing">Video Link Of Level Select Screen</a>
The idea here was simple, the level select screen is also a level.
<br>
Each level requires knownledge of certain mechanics but I didn't want to teach the players the mechanics in the level because it was going to be a competition between you and your friends. So I had to teach the players beforehand. Making tutorial levels seemed excessive but the level select screen could in itself be all the tutorial levels required.
<br>
So, once the level unlocked. You and your friends could only agree on the level if you had learned the mechanics that will be further explored in the level. 
<br>
For example since you are slimes you can stick to the ceiling, to get to the level that explores that idea, you need to learn that you CAN stick to the ceiling. Hints as to what to do would also appear in the level select screen.
<br>
<br>
-------------------------MECHANICS-------------------------
The main mechanic is that you dont have a jump button or a duck button you can only create a force vector in any direction.
<br>
It's up to you to figure out how to best use that force vector given the scenario.
<br>
<a href="https://drive.google.com/file/d/122daJ87Oiq5QSQomuUQiHK27wYGqPPhb/view?usp=sharing">Link To Density Changes</a>
Moving towards an object increases your density and decreases your volume
<br>
Moving away from an object decreases your density and increases your volume
<br>
<a href="https://drive.google.com/file/d/1Yi4nZxZyUNieWoPUwPXL6RkmWPJmOBUd/view?usp=sharing">Link To Easy Surface Transitions</a>
You can only create 8 direction with your 4 buttons. But you should be able to properly move on any surface; and you should be able to move between surfaces of different types.
<br>
<br>
<a href="https://drive.google.com/file/d/15aA1vnc8OgIRAt_8WsQKU9clUQU2O3i3/view?usp=sharing">Link To Using Your Force Vector Properly</a>
If you are trying to move the fastest way possible along a surface then its important to not waste some of your force pushing yourself towards it.
<br>
Then again it might be important to waste some of it to do this if you are trying to avoid being knocked of the edge by one of your friends or perhaps a gust of wind or super strong gravity.
<br>
<br>
<a href="https://drive.google.com/file/d/11a7MEm2PmURs_FFAFDyFQdkb1VH2WWDJ/view?usp=sharing">Link To In Game Health</a>
Your size is indicative of how much health you have and when you are on the verge of death so is your shape.
<br>
<br>
<a href="https://drive.google.com/file/d/12N-icSKZJjdlLsNuFNcqQwH6KqB2Ibv6/view?usp=sharing">Link to How Your Health Matters</a>
<br>
But the more health you have the slower you move, I was hoping this would create a natural balancing effect.
