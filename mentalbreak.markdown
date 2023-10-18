---
layout: content
title: Mental Break - Game Jam
permalink: /mentalbreak/
---
# Mental Break - Weeklong Game Jam <!--Potentiall update to a mid physical play photo.-->
<img style="padding: 1rem;" src ="/assets/images/mentalBreak/gameplay.gif" alt = "Gameplay Gif of Mental Break" width = "500 rem" align = "left" />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This project was a weeklong game jam that my team and I created based on the prompt of “Break”. Our team chose to work in Gamemaker as other members were more familiar with it than other engines and it was quicker to create a working product. I was the lead programmer on the project, writing more than 90% of the code and creating the architecture of the file system and the way assets were implemented.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This code includes managing the states of each character, enforcing combat boundaries, camera management, and enemy AI. The enemies’ AI uses a state machine to manage the different game states they could occupy, such as Idle, attacking from different directions, or queueing to fight, so as to not overwhelm the player. This is all implemented in an extensible way, allowing for easy expansion of features, attacks, and systems while also making the implementation and polishing of assets quite easy for other developers.

<img style="display: block;margin-left: auto; margin-right: auto;" src ="/assets/images/mentalBreak/testing.jpg" alt = "Testing Image of Mental Break" width = "60%"  />

---
<iframe frameborder="0" src="https://itch.io/embed/2315714?bg_color=0d133e&amp;fg_color=de06fb&amp;border_color=644f9f" width="552" height="167"><a href="https://u-t3am.itch.io/mental-break">Mental Break by U T3am, thethirdfalcon, lotus45, LittleTrout, eric1223, Abheek Bajaj</a></iframe>