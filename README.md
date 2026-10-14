# PAPERHEAD-VR
Mod for PAPERHEAD VR


PAPERHEAD VR  -  VR mod for "PAPERHEAD" (Unity 6000.4, HDRP, Mono x64)
=====================================================================

Version 0.1.5 (test build Quest 3 VDXR).

WHAT IT DOES
------------
* Stereo VR through OpenXR (SteamVR, Meta/Oculus Link, Virtual Desktop, WMR...).
* First person: your headset is the player's head. The game camera turns with your head, so walking
  and the game's look follow where you look. Left stick walks, right stick snap-turns.
* 6DOF weapon: the weapon sits in your right controller and shoots where it points (red laser).
* Cutscenes / other game cameras: you sit at that camera.
* The VR controllers are an Xbox controller for the game (fed straight into the game's Rewired input).
* HUD and menus are on a screen floating in front of you.

INSTALL
-------
1. Copy zip into the game folder (merge / overwrite).
2. Start your VR runtime (SteamVR, Quest Link / Air Link, Virtual Desktop) first, then the game.

CONTROLS (the game's own gamepad layout; Xbox buttons in brackets)
--------------------------------------------------------------------
Right stick up / down ...... d-pad up / down

Left stick click + right stick left / right ... d-pad left / right

X + Y together .. Start (pause)

A + B together .... Back / View

In menus: left stick / d-pad move, A = confirm, B = back.

IN-GAME VR SETTINGS:    hold Y + left stick click for 1.7 s.

WEAPON ADJUST (live):   hold BOTH stick clicks 1.7 s with a weapon out - hold the left grip to grab the
                        weapon and move / turn it, right stick up/down = size, B = default, A = save
                        
LASER ADJUST (live):    hold BOTH grips 1.7 s, let go, then left grip = move the start point onto the
                        muzzle, right stick = steer the laser, B = default, A = save.
                        
HAND ADJUST:            hold Y + right stick click for 1.5 s.
Every button can be changed in [Controls] of BepInEx\config\paperhead.vr.cfg; a game action can be
moved to another gamepad button with [Input] ActionOverrides.

