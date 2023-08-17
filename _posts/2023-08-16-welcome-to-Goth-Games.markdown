---
layout: post
title:  "Welcome to Goth Games!"
date:   2023-08-16 14:08:06 -0700
categories: siteupdate
---
This is a game dev blog. Let me describe the first game I will be making under the brand name, "Goth Games" and how I am making it.

## What's in it?
* You play as a man with medievel weapons and armor.
* Your guy can block, evade, and attack enemies.
* The camera is in a third-person perspective and it can lock onto targets.
* There is a town populated with NPCs that you can talk to.
* There is a wildnerness zone sparsely populated with NPCs and enemies, as well as some hidden rewards.
* There is a dungeon densely populated with enemies and with rewards for killing the enemies.
* If you clear the dungeon, you complete the game.

This may sound pretty simple and straightforward, and I hope that it is. I want this initial project to serve as a "base game" that can be expanded into a much larger game with multiple towns, regions, dungeons, treasures, and quests. I also want this game to be as easy as possible to make mods for, which leads me to the next topic.

## How will you make it?
I am sticking to open source tools and free assets. I already made the mistake of spending money on professional software that I ended up not using. I also absolutely want to minimize my risk of being rug-pulled by some corporation changing their ToS or EULA or whatever. Lastly, I have deemed that the tools below are perfectly adequate for the job and may actually help with one of my main goals: mod support.
### Engine
The game is being developed in the [Godot][godot] engine. Mods will be made using the same engine. I am striving for clean and readable code, but I am a novice programmer myself, so this has been an interative process. The structure of the game will be as follows:
* The game will be made of multiple scenes.
* Scenes will contain multile subscenes.
* Subscenes will contain multiple nodes.
* Nodes will have attached scripts and resources.
* Scripts contain functions.
* Resources include meshes, animations, sounds, shapes, textures.

A beginner modder will be able to rearrange Subscenes within a Scene to redesign the environment. An experienced modder will be able to create new Scenes and Subscenes, as well as modify resources. An advanced modder will be able to edit scripts and add new functionality.
### 3D Assets
I am developing 3D assets in [Blender][blender] which are then exported to [gLTF][gltf] format to be used by the engine. Modders can use Blender as well, or another software if it can export to the gLTF format. I will provide documentation on rigging, texturing, and other details to help modders produce assets that can be easily integrated. Where I am not making assets from scratch, I am using assets provided with the [CC0 License][cc0].
### Music
I do not know yet. I know what style I am looking for but I don't have any musical talent. I haven't found any free music that I like, either.
### Sounds
I have not begun to create or acquire sound assets. I expect that I will rely mostly on sounds with the CC0 License. Any editing will be done in [Audacity][audacity] or similar.


## When can I play your game?
I do not know. I am already 6 weeks behind my own schedule. Maybe there will be something by the end of 2023.


[godot]:https://godotengine.org/
[blender]:https://www.blender.org/
[gltf]:https://www.khronos.org/gltf/
[cc0]:https://creativecommons.org/share-your-work/public-domain/cc0/
[audacity]:https://www.audacityteam.org/
