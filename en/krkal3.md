---
layout: mainen
title: KRKAL 3
lang: en
---
# Krkal 3

Krkal 3 is an unfinished game engine.

It was created as a diploma thesis at the MFF-UK in 2007. I tried to remove the ailments from version 2.4. I've completely rewritten the entire scripting language and wrote a new compiler. Krkal is now formed by replaceable modules, which means far more general usability. Work stopped in 2009. Components relative to the language and the compiler are finished. Thanks to the modularity they could be well used in another game engine. Unfortunately this is not enough to revive Krkal (or other game) in version 3.0.

## Main benefits of the Krkal system:
Special object oriented language, which is able to easily describe simulation of various, interacting game objects. And one that allows easy expandability. Anytime you have a game with multiple objects, which are somehow living, mutually influencing one another, you have a multitude of general and special rules and you know that new objects and rules are on their way, then Krkal is the clear choice.

## Other features
* **Krkal is object oriented.**  
* **Krkal is based on scripting.**  
* Objects are alive and mutually influence each other. Communication and synchronization is provided by a **message sending system**.  
* **Krkal is set oriented.** Everything that you named, you can group into sets. (Objects, methods, graphics, abstract concepts ...) Sets on one hand impact the behavior of the system, and on the other hand you can work with them directly in the scripts, there is a special type for sets. An example can be object inheritance:  
* **Multiple inheritance.** Do you want to create a new object, which can be 1) pushed 2) destroyed 3) will explode upon destruction 4) falls into holes 5) moved by conveyor belts 6) snails fear it... Simply inherit it from predecessors with desired properties and that's all!  
* **Expandability.** Scripting and the entire Krkal are designed in a way, which allows to simply intervention into the games. You can for example come up with a special mischievous monster, property, change of rules,... and add it into one level. Krkal is designed to make this simple and you did not have to go back and rewrite half the code for this. (All this thanks to inheritance, sets, safe methods and versioning.)  
* **Versioning.** Right from the starts Krkal is designed to enable simultaneous work on the game to multiple people. Krkal on one side makes sure that people don't infringe on one another, and along with that also makes sure that all modifications can be combined and that they work.  
* **Supporting language localizations.**  
* **Simplicity**  
* **Security**  
* **Power** - play Krkal and you'll understand what the engine can do and this is the absolute first version.    
* **Krkal is not a library of functions**, but a runtime, which takes care of game objects.  
* **Modularity** - plug Krkal in your own engine.  
* Compiler converts Krkal C to C++ and that is than converted to a dll module.
* Compiler can cooperate with an editor; it provides a type information and information for smart suggestion while typing (Intellisense).

## Krkal 3.0 components: 
**Already completed (or almost):**  
Compiler, Code Generator, Integrated Environment for script writing (today it would be better to integrate into MS Visual Studio), Krkal Runtime (Kernel), File System and Sample Application, which brings everything together and works as a demo. 

**ToDo:**  
New graphics engine, Level Editor, or component for game GUI, Hud, ... 

[Source codes at GitHub](https://github.com/HonzaMD/Krkal3)  
[Diploma thesis](/dl/JazykProRizeni2DHer.pdf)
