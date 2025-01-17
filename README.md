# Nexus-Engine
This engine was originally made for the [Dave and Bambi: Nexus edition](https://gamebanana.com/mods/564377), now it is an actual engine
Nexus Engine is a modified version of Psych Engine



# Compilation:
not that hard, use the same ones as psych engine 1.0 please, PLEEEEEASSSSSSSSSSSSSSEEEEEEEEEEEEEE

Here it is: [the Build Instructions of Psych Engine 1.0](./BUILDING.md)

## Customization In Source Code:

if you wish to disable things like *Lua Scripts* or *Video Cutscenes*, you can read over to [Project.xml](./Project.xml)

inside [Project.xml](./Project.xml), you will find several variables to customize Nexus Engine to your liking

* If you are making a mod in source code, you would want to change the name of the window, as Nexus engine is kind of boring while the mod is made in source code
for that you will have to head to line 5 or <app title="... there in the string, you would want to change the name of the window, if you also want to change the name of the app, like Nexusengine.exe
you would want to change the file="" string, to your liking (remember, changing the name of the app like the memodyay.exe will result in a couple error if you did any changes to playstate.hx or pausesubstate, so first rename everything and then do all the coding)

*if you want to disable videos for some reason, delete the line that says 
<define name="VIDEOS_ALLOWED...

*would you really want to do this?????????
if you want to change the window from landscape to portrait, change the lines: 52, 55, 58 I guess??..


## Credits:
# Nexus Engine Developers
* Dragos - Developer, Main programmer
* Snare - Artist, Musician

# Psych engine Developers
* Shadow Mario - Head Developer, Programmer.
* Riveren - Main Artist.

### Special Thanks
* An Ammar - Inspiration
* bbpanzu - Ex-Team Member (Programmer).
* crowplexus - HScript Iris, Input System v3, and Other PRs.
* Kamizeta - Creator of Pessy, Psych Engine's mascot.
* MaxNeton - Loading Screen Easter Egg Artist/Animator.
* Keoiki - Note Splash Animations and Latin Alphabet.
* SqirraRNG - Crash Handler and Base code for Chart Editor's Waveform.
* EliteMasterEric - Runtime Shaders support and Other PRs.
* MAJigsaw77 - .MP4 Video Loader Library (hxvlc).
* Tahir Toprak Karabekiroglu - Note Splash Editor and Other PRs.
* iFlicky - Composer of Psync, Tea Time and some sound effects.
* KadeDev - Fixed some issues on Chart Editor and Other PRs.
* superpowers04 - LUA JIT Fork.
* CheemsAndFriends - Creator of FlxAnimate.
* Ezhalt - Pessy's Easter Egg Jingle.
* MaliciousBunny - Video for the Final Update.
_____________________________________

# Features

## Mod Support
* Probably one of the main points of this engine, you can code in .lua files outside of the source code, making your own weeks without even messing with the source!
* Comes with a Mod Organizing/Disabling Menu.
* Will have mod support for 0.6.3, #KEEP IN MIND, THE ENGINE WILL NOT UPDATED UNTIL WE FINISH THE MOD

## Cool new Chart Editor changes and countless bug fixes
*Lil' Buddies

## Multiple editors to assist you in making your own Mod
![Screenshot_3](https://user-images.githubusercontent.com/44785097/144629914-1fe55999-2f18-4cc1-bc70-afe616d74ae5.png)
* Working both for Source code modding and Downloaded builds!

## Story mode menu rework:
![](https://i.imgur.com/UB2EKpV.png)
* Added a different BG to every song (less Tutorial)
* All menu characters are now in individual spritesheets, makes modding it easier.

## Credits menu
![Screenshot_1](https://user-images.githubusercontent.com/44785097/144632635-f263fb22-b879-4d6b-96d6-865e9562b907.png)
* You can add a head icon, name, description and a Redirect link for when the player presses Enter while the item is currently selected.

## Awards/Achievements
* The engine comes with 16 example achievements that you can mess with and learn how it works (Check Achievements.hx and search for "checkForAchievement" on PlayState.hx)

## Options menu:
* You can change Note colors, Delay and Combo Offset, Controls and Preferences there.
* On Preferences you can toggle Downscroll, Middlescroll, Anti-Aliasing, Framerate, Low Quality, Note Splashes, Flashing Lights, etc.

## Other gameplay features:
* Cool Animations
* 3D healthbar (the healthbar has the camera set to gamecam, possible to change with lua)
* When the enemy hits a note, their strum note also glows.
* Lag doesn't impact the camera movement and player icon scaling anymore.
* Some stuff based on Week 7's changes has been put in (Background colors on Freeplay, Note splashes)
* You can reset your Score on Freeplay/Story Mode by pressing Reset button.
* You can enable "Combo Stacking" in Gameplay Options. This causes the combo sprites to just be one sprite with an animation rather than sprites spawning each note hit.
