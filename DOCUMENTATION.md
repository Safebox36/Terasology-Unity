## Introduction
The Terasology project was born from a Minecraft-inspired tech demo and is becoming a stable platform for various types of gameplay settings in a voxel world. There are several attempts to make clones of Minecraft but most have either fallen into obscurity, lack in features or have been dropped by their develops. Terasology on the other hand is still going strong just over six years later despite only now hitting the final release of version 1 (alpha 9). I myself went in search of an open-source Minecraft clone / engine after the asset I'd previously been using became depreciated on the Unity Asset Store due to the commercial infeasibility of supporting it. Having it exist in Unity would benefit the indie community greatly as it would provide only allow a free alternative to some of the commercial assets on the Asset Store but also allow for the creation of non-voxel games that require the need for a "3D tileset" aesthetic. My hope from this project is that developers will work on both the Unity version and the original Java version collaboratively to provide an incredible voxel engine, game and modules for years to come.

I would like to personally thank the developers of Terasology for doing an amazing job and continuing to support the project as the team at MovingBlocks continues to grow.
## Aims
My aim for this project is to convert Terasology from Java to C# for use in the Unity3D game engine, ambiguous of gameplay elements or assets used. All code will be converted as faithfully as possible, even if redundant, to allow for conversion into other game engines that may not have the same functions.
## Standardisations
In order to convert the code as close to the original as possible, some standardisations have to be made. They are as follows:
- All **math functions** will use **TeraMath and Terasology** with a wrapper around **UnityEngine** to allow for a familiar code structure with a reduced level of, what is essentially, duplicate functionality.
- **Static code blocks** in Java will be implemented using **static constructors** in Unity.
- If **interface** is not used then it will be **implemented regardless**.
## Plan
- [] Stage 1 - Gestalt Java to C# code conversion
- [] Stage 2 - TeraMath Java to C# code conversion
- [] Stage 3 - Terasology Java to C# code conversion
- [] Stage 4 - Reduce / Replace Terasology libraries with Unity equivalent
## Progress
### 0 – Unity Setup	(5/2/18)
Unity 2017.3.1f1 will be used for this project with version 1.6.0 (Alpha 9) of Terasology being used for conversion.