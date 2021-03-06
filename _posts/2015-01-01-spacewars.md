---
layout: post
title: Spacewars
category: Games
tags: [Python, Game]
---

This is the first game I ever completed. I really enjoyed making it since it made me learn so much about how games are made, new approach to certain problems, objects management, OpenGL and much more.

[![spacewar_4](/public/img/games/spacewar/spacewar_4.png)](/public/img/games/spacewar/spacewar_4.png)
<!-- more -->

It is based on the game Spacewar (the version released in 1985), a fun game I used to play on a Compaq Portable III with my brothers.
It is a 1 vs 1 game where you have to destroy the opponent. Your ship is equipped with laser, missiles, cloak, energy shield, a random teleportation device and the ability to convert your energy from and to the hull integrity.

The ‘’combat zone’’, which is looping back when you go through the side, can include asteroid and/or a central planet. The asteroids move around the map, hurt the players on contact and can be destroy if you shoot at them enough. The planet sits in the middle of the map and while they don’t hurt the players on contact, their gravity affect most objects in the game (player, bullet, asteroids). If a player gets stuck to the surface of the planet, it is hard to get away and the player becomes an easy target.

**About Panda3D**: Panda3D is an open source C++ game engine with python binding. Super nice community!

The code is avaible in my repository my repository [Panda3D-Space-Wars](https://github.com/martinrioux/Panda3D-Space-Wars).
{: .text-justify}

Here a some screenshots:

| [![spacewar_1](/public/img/games/spacewar/spacewar_1.png)](/public/img/games/spacewar/spacewar_1.png) | [![spacewar_2](/public/img/games/spacewar/spacewar_2.png)](/public/img/games/spacewar/spacewar_2.png) |
| [![spacewar_3](/public/img/games/spacewar/spacewar_3.png)](/public/img/games/spacewar/spacewar_3.png) | |
{: .no-border}