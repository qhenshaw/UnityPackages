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
```
https://github.com/qhenshaw/SharedSampleAssets.git
```

### Editor
[Editor Tools](https://github.com/qhenshaw/EditorTools): A collection of useful editor tools focused on organization, level design, and lighting.
```
https://github.com/qhenshaw/EditorTools.git
```

### Scripting Systems
[Game Events](https://github.com/qhenshaw/GameEvents): A scriptable object based inspector editable event system useful for decoupling prefabs across scenes.
```
https://github.com/qhenshaw/GameEvents.git
```


### Interface
[UI Components](https://github.com/qhenshaw/UIComponents): A collection of useful UI components with a functional main menu / gameplay sample scenes.
```
https://github.com/qhenshaw/UIComponents.git
```

### Gameplay
[Character Movement](https://github.com/qhenshaw/CharacterMovement): 3D and 2D movement components with sample scenes for a variety of movement setups.
```
https://github.com/qhenshaw/CharacterMovement.git
```

[Local Multiplayer](https://github.com/qhenshaw/LocalMultiplayer): A functional local multiplayer setup with a player join screen. Uses CharacterMovement and GameEvents packages.
```
https://github.com/qhenshaw/LocalMultiplayer.git
```

### Rendering
[Renderer Features](https://github.com/qhenshaw/RendererFeatures): A collection of URP renderer features.
```
https://github.com/qhenshaw/RendererFeatures.git
```

### Audio
[FMOD Extensions](https://github.com/qhenshaw/FMODExtensions): A collection of scripts useful for playing FMOD audio in Unity.
```
https://github.com/qhenshaw/FMODExtensions.git
```

### Debugging
[Debug Menu](https://github.com/qhenshaw/DebugMenu): An extensible debug menu.
```
https://github.com/qhenshaw/DebugMenu.git
```

### Performance
[Object Pooling](https://github.com/qhenshaw/ObjectPooling): A lazy initialized object pooling system built on Unity's Pooling collections.
```
https://github.com/qhenshaw/ObjectPooling.git
```
