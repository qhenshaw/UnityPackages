# Unity Packages
[![Unity 2021.3+](https://img.shields.io/badge/unity-2021.3%2B-blue.svg)](https://unity3d.com/get-unity/download)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](LICENSE.md)  
This is a meta repo documenting all of the Unity packages I'm maintaining.

## System Requirements
Unity 2021.3+. Will likely work on earlier versions but this is the version I tested with.  
Most packages are URP/HDRP agnostic, aside from anything in the rendering section. You may have to fix some materials in the SharedSampleAssets.

## Installation
Use the Package Manager and use Add package from git URL, using any of the following .git URLs. Some packages have dependencies, check the documentation.

## The Packages  
Most packages come with samples demonstrating functionality and providing a starting point for further development.

### Assets (Required Installation)
[Shared Sample Assets](https://github.com/qhenshaw/SharedSampleAssets): A collection of shared assets used in the following packages.  

### Editor
[Editor Tools](https://github.com/qhenshaw/EditorTools): A collection of useful editor tools focused on organization, level design, and lighting.  
[Terrain Automation](https://github.com/qhenshaw/TerrainAutomation): Rapidly iterate on terrain designs by procedurally placing trees and details based on height and splat maps generated through apps like Gaea.  

### Scripting Systems
[Game Events](https://github.com/qhenshaw/GameEvents): A scriptable object based inspector editable event system useful for decoupling prefabs across scenes.  

### Interface
[UI Components](https://github.com/qhenshaw/UIComponents): A collection of useful UI components with a functional main menu / gameplay sample scenes.  

### Gameplay
[Character Movement](https://github.com/qhenshaw/CharacterMovement): 3D and 2D movement components with sample scenes for a variety of movement setups.  
[Local Multiplayer](https://github.com/qhenshaw/LocalMultiplayer): A functional local multiplayer setup with a player join screen. Uses CharacterMovement and GameEvents packages.  

### Rendering
[Renderer Features](https://github.com/qhenshaw/RendererFeatures): A collection of URP renderer features.  

### Audio
[FMOD Extensions](https://github.com/qhenshaw/FMODExtensions): A collection of scripts useful for playing FMOD audio in Unity.  

### Debugging
[Debug Menu](https://github.com/qhenshaw/DebugMenu): An extensible debug menu.  

### Performance
[Object Pooling](https://github.com/qhenshaw/ObjectPooling): A lazy initialized object pooling system built on Unity's Pooling collections.  
[HLOD System](https://github.com/qhenshaw/HLODSystem): A fork of the Unity HLOD package with the mesh UnityMeshSimplifier scripts added to avoid Git sub-modules.
