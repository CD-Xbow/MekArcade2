MEKARCADE 031 ROADSIDE PACK

Description: 	A collection of 50+ low poly road side signs and objects
Version:	031
Artists: 	CD Xbow, Gabriella, QkennyQ, Sitters, Nobiax
File Format: 	md3
		Configuration for the Cube engine
File size: 	 zipped,  unzipped
Publisher: 	TeamXbow
Release: 	Official release with Mekarcade 0.31
Licence: 	CC-SA 3.0 licensing unless otherwise stated.

Contents: 
50+ models of roadsigns and other road releated objects. The models are fairly basic at this stage and simply textured. The general look is suitable for 20th century onwards. We have reused skins and meshes to save space.  

We hope you enjoy the models and make good use of them. If you mod 'em, please send
them back to us, we'd love to see your work. If you improve them we would include 
them in the next release if you don't object.

In the next iteration we may finish adding spec/normal maps, bone 'em, and turn them into animated md5s so the meka can squish them. I will probably only do this the international signs and they will be in the release version. 

Remember most of these things are tiny in a mek game.

Enjoy!

STATIC MODELS  _____________________________________________________________


ad1 x4		:4 simple roadside in directories numbered 1 to 4
ad2		:rounded roadside ads
ad50 		:50's style mesh, with 2 skins
arrows		:Black and white
barrier		:concrete barrier
boom		:boom gate
fuelpump	:Excellant low poly fuel pump By QkennyQ - see readme.
giveway
intl		:13 different international signs 
ohsign1		:Single freeway type overhead sign
ohsign2		:Double freeway type overhead sign
pile_sand	:x3 sand, plus 2 using wiked textures
postbox		:classic 20C postbox
railway		:signal
rubble 		:that bit of rubble
speed 		:20, 60, 120 and none in their own directories
stop		:
streetlight1	:streetlight
streetlight2	:animated falling streetlight
trafficlight x4	:four different traffic lights
tunnel 		:front of a tunnel
warn		:5 different warnings in their own directories 
xing		:Peadestrian crossing sign

ANIMATED MODELS  _______________________________________________________________

model:	  	streetlight2.md3
use:		Designed for MekArcade as a 'knockover' mapmodel, configured for RE
creator:	cd xbow
stats:		vertices: 132
          	polygons: 156
          	skins: 1

description:	A very simply falling street lamp for use with the triggers in MekArcade/RE, this was about my first animation
		
copyright:	Released under the GNU GENERAL PUBLIC LICENSE

status: 	Works. Haven't figured out how to keep it down!




config:

//streetlamp2 working config
md3load tris.md3
md3skin mesh1 skin.jpg
md3anim "mapmodel" 0 1   // 
md3anim "trigger on" 0 10 10    //
md3anim "trigger off" 10 10 10    // 

//mdlbb 4
mdlscale 40  //40 for MekArcade, 100 about right for RE
mdlspec 100

		       