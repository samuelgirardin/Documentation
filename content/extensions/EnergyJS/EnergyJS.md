
## EnergyJS

# Introduction

EnergyJS is a  3d physic engine. One more ? We already have CannonJS & OimoJS working well with BJS physic  plugin. So why working on a third one ? 
EnergyJS is a bit different. Unlike Cannon&Oimo, EnergyJS is not 100% written in classic JS. EnergyJS is a port of the c++ project Open dynamic Engine by Russel Smith made possible with the  Emscripten framework. Basically you can resume this process by  :  ode c++ sources → Emscripten compiler → output low level javascript file. This last file is a 'clone' of the c++ engine, it will behave exactly like  a c++ build. In order to use it with babylonjs we need a typescrpit interface/wrapper to communincate with it. 

* Pros : really fast, high accuracy, good stacking, well documented (ode's doc), asm.js & webAssembly ready

* Cons : js sources unreadable, c++ to js workflow is not public at the moment, bjs physic plugin will not be avalable during the alpha version (energy code may change).

# Demos

* [car & trailers](http://www.visualiser.fr/energy/index.php?ID=1)

Tuto1_friction

Tuto2_friction2

Tuto3_bounce

Tuto4_rolling_friction

Tuto5_rolling_friction2

Tuto6_contact_cfm_erp

Tuto7_contact_cfm_erp2

Tuto8_motion

Tuto1_auto_disable_body

WoodMachine

BallJoint

Trimeshes

Vehicle   (maybe you need to refresh the html page - loading is async and I forgot to fix that,, same for v+trailers)

Vehicle+trailers (arrow key to control the vehicle, d to flip the vehicle)












