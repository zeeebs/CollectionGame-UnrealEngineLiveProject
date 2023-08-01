#Collection Game - Unreal Engine Live Project

<p id="Page Top">
StackOBot Collection Game using Unreal Engine

This project was created using Unreal Engine. It showcases landscaping, a graphical health bar with a damage system, a self-updating collectibles system also with a graphical component, scene switches, and sound effects and music. 

After completing the Tech Academy's C++ and Unreal Engine Course of the Game Developer Bootcamp, I worked along side other students during a two-week Sprint to develop a full-scale game. I had free range to create virtually any game I wanted, which allowed for a lot of learning oportunities. Since the development was all done on an individual level, I developed the back-end and front-end aspects of the game. Through this project, I became comfortable using Unreal Engine and I am very excited to keep exploring the vast features it has to offer.


Below are descriptions of the features I made for my game, along with images of my blueprints and final product images.
<ul>
<li><a href="#CollectibleSystem">Collectible System</a></li>
<li><a href="#HealthSystem">Health System</a></li>
<li><a href="#DamageSystem">Damage System</a></li>
<li><a href="#Scene Switches">Scene Switches</a></li>
<li><a href="#Other Skills">Other Skills</a></li>
<li><a href="#Images">Images</a></li>
 </ul>
 </p>
 
<hr class="dashed">

<p id="CollectibleSystem">
<h3>Collectible System</h3>
 
The objective of the game is to collect all 30 orbs without dying. Upon collision, the orb is destroyed and the HUD reduces the total amount of orbs left by one. For added UI, a sound is played when the orb is collected.

<h4>Collectibles Count Blueprint</h4>Collectibles Count Blueprint

![Collectibles Count Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/CollectCount.png)

<h4>Collectibles HUD Blueprint</h4>

![Collectibles HUD Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/CollectHUD.png)

<h4>Collectibles Create HUD Blueprint</h4>

![Collectibles Create HUD Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/CreateHUD.png)

<h4>Collectibles Sound and Destroy Blueprint</h4>

![Collectibles Sound and Destroy Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/CollectSoundDestroy.png)

<h4>Winning Blueprint</h4>

![Winning Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/YouWin.png)

</p>
<p id="HealthSystem">
<h3>Health System</h3>

The main obstacle in the game is the floating platforms that need to be traversed to move from one structure to another in order to collect the orbs. If you fall, you may lose health. If there is damage, the health bar will change to reflect the lost health.

<h4>Health Widget Blueprint</h4>

![Health Widget Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/HealthWidget.png)

<h4>Create Health Widget Blueprint</h4>

![Create Health Widget Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/CreateHealthWidget.png)

</p>
<p id="DamageSystem">
<h3>Damage System</h3>
The damage system is triggered using time, so losing health is determined by how long the player is falling for. If the fall is over one second, the player will lose health at intervals of 25%. If the player dies, the game ends.

<h4>Damage System Blueprint</h4>

![Damage System Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/DamageSystem.png)

<h4>Receive Damage Blueprint</h4>

![Receive Damage Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/ReceiveDamage.png)

<h4>Game Over Blueprint</h4>

![Game Over Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/GameOver.png)

</p>
<p id="Scene Switches">    
<h3>Scene Switches</h3>

There are 3 scene switches. This includes a main menu scene to play the game, the game over scene when the player dies, and a scene for when the player is successful in collecting all 30 orbs. The main menu scene has a play button and a quit button. The game over and winning scenes have a retry button, a quit button, and a main menu button.

<h4>Main Menu Blueprint</h4>

![Main Menu Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/MainMenu.png)

<h4>Win Menu Blueprint</h4>

![Win Menu Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/WinMenu.png)

<h4>Game Over Menu Blueprint</h4>

![Game Over Menu Blueprint](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/LoseMenu.png)

</p>
<p id="Other Skills">
<h3>Other Skills</h3>
<ul>
<li>Creating a level from scratch. I learned the value of creating a rough draft prior to beginning development. I did a lot of it just as I went which made for some frustration and lack of direction. Planning out the game ahead first would have been very helpful.</li>
<li>Gaining more experience with Unreal Engine and becoming more comfortable using blueprints instead of written code.</li>
<li>Utilizing pre-made features from Unreal Engine and modifying them to work with my game.</li>
</ul>

</p>
<p id="Images">
<h3>Images</h3>

Lastly, here are some images from the final product.

![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/StartMenu.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/YouWinMenu.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/GameOverMenu.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/inGame.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/Platforms.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/landscaping1.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/landscaping2.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/landscaping3.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/fromAbove.png)
![Game Image](https://github.com/zeeebs/CollectionGame-UnrealEngineLiveProject/blob/main/img/sideView.png)
  
<h4><a href="#CollectibleSystem">Collectible System</a>, <a href="#HealthSystem">Health System</a>, <a href="#DamageSystem">Damage System</a>, <a href="#Scene Switches">Scene Switches</a>, <a href="#Other Skills">Other Skills</a>, <a href="#Images">Images</a>, <a href="#Page Top">Page Top</a></h4>
