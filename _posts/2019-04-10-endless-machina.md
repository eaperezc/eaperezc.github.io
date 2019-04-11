---
layout: post
permalink: /blog/endless-machina
title: Endless Machina
tags: [videogames, demos, unity3d]
feature-img: "assets/img/endless/endless1.png"
---

This next game was actually released for a while for mobile. It was one of the projects we enjoyed the most building because of a lot of reasons that I'm gonna try to talk about on this post.

Let's get started!

## Game origin

Now that we have a little bit more knowledge on how to build games using Unity3D we felt that we needed to play a little bit more with 2D games using the engine. All of our other games were done with 3D models so this was a new challenge that we wanted to try. 

![Honor And Glory Battle]({{ site.baseurl }}/assets/img/endless/endless4.png)

Endless Machina is a labyrinth game where the player have to avoid touching any of the walls, obstacles or enemies. One of the most interesting things we wanted to build for this game was automatic level generation. And we actually did! The player could play "endlessly" and there would always be a "next level" for them.  

![Honor And Glory Battle]({{ site.baseurl }}/assets/img/endless/endless1.png)

One interesting thing about this project is that we didn't have the 2D tools that the newest Unity versions have, so imagine building a 2D game with unity without animator, sprite editors, 2D spritesheet management, etc. Those were fun times. 

## Most important features 

As usual I'm gonna list the features of the game:

* Our first 2D game in Unity
* Automatically generated levels (infinite playtime)
* Facebook account sync 
* Achievements system and rewards
* Collectibles and Scores

And... This doesn't count anymore but were using an old service to generate video content called Everyplay. Any player was able to "record" his gameplay directly from the app and post it to the platform. 

## Infinite levels

Being only 2 people working on the project we needed to make sure we had a way to create content for the players in a way that could scale without us having to manually create the levels. I'm really proud of the result because I created a level builder abstraction that generated levels based on the player level, score and available "obstacles". 

![Honor And Glory Battle]({{ site.baseurl }}/assets/img/endless/endless2.png)

The idea came from a game I was playing at the time called Torchlight. Those guys created infinite dungeons based on some pre-built level tiles so I basically wanted to do the same thing but in a 2D environment.

If I remember correctly, we had over 50 different types of pre-built obstacles and we connected them depending on some calculations. It was really fun to get that working. There was a challenge there because we couldn't let the builder go nuts trying to avoid collisions between tiles. 

## Did we learn something?

First 2D game so I learned how to work with spreadsheets and 2d animations. Had to flip a switch on my mind between Vector3 to Vector2 but that was basically most of the learning when coming from a 3D to 2D so, well done Unity. Of course now with the newer versions all of this is more and more easy to build, I totally recommend you check it out if you can. 

![Honor And Glory Battle]({{ site.baseurl }}/assets/img/endless/endless4.png)

At the end of the day we had to unpublish the game but we loved this project. We are working on another version of this game and I'll write about that one as soon as it's ready to play. 