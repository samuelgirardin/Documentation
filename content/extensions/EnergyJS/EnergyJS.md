
# EnergyJS

## Introduction

EnergyJS is a  3d physic engine. One more ? We already have CannonJS & OimoJS working well with BJS physic  plugin. So why working on a third one ? 
EnergyJS is a bit different. Unlike Cannon&Oimo, EnergyJS is not 100% written in classic JS. EnergyJS is a port of the c++ project Open dynamic Engine by Russel Smith made possible with the  Emscripten framework. Basically you can resume this process by  :  ode c++ sources → Emscripten compiler → output low level javascript file. This last file is a 'clone' of the c++ engine, it will behave exactly like  a c++ build. In order to use it with babylonjs we need a typescrpit interface/wrapper to communincate with it. 

* Pros : really fast, high accuracy, good stacking, well documented (ode's doc), asm.js & webAssembly ready

* Cons : js sources unreadable, c++ to js workflow is not public at the moment, bjs physic plugin will not be avalable during the alpha version (energy code may change).

## Demos

* [car & trailers](http://www.visualiser.fr/energy/index.php?ID=1)
* [trimeshes collision](http://www.visualiser.fr/energy/index.php?ID=15)
* [ballJoint](http://www.visualiser.fr/energy/index.php?ID=13)
* [woodMachine](http://www.visualiser.fr/energy/index.php?ID=12)

## Features
this list is not exhaustive. To be completed.
* dynamic body proporties
* [friction]
* [friction2]
* [bounce]
* [rolling_friction]
* [rolling_friction2]
* [contact_cfm_erp]
* [contact_cfm_erp2]
* [motion]
* [auto_disable_body]












