# uFrame Entity Component System
![](https://www.lahc.edu/pageunderconstruction.png)
Welcome to the uFrame Entity Component Documentation!

## Overview
- [Components](API/Components.md)
- [Groups](API/Groups.md)
- [Systems](API/Systems.md)
- [Handlers](API/Handlers.md)
- [Events](API/Events.md)
- [The Entity Component](API/EntityComponent.md)
- [Custom Actions](API/CreateCustomActions.md)

## Tutorials
- [Getting Started - Project Setup](https://youtu.be/uxivyGL5StA)
- [Creating Components - Hello World Example](https://youtu.be/vGRgN-MZEAA)
- [Creating And Using Groups - Component Matching](https://youtu.be/5EwZWWfpBBI)
- [Creating And Using Groups 2 - Expression Filtering](https://youtu.be/iMjs26dA2rg)
- [Creating And Using Custom Events](https://youtu.be/h_s-l30rNe0)
- [Creating Custom Actions](https://youtu.be/AuockvC5Cys)

# Installing ECS From Github - With or Without Editor
If you want quicker updates to the core framework, you can always install directly from the source code.  Or if you want to use uFrame ecs without the designer tools, its completely free.

Clone each of the repositories and replace the following directories in the following locations.

#### Invert.Common - Free Open Source
Attributes and IOC Container
https://github.com/InvertGames/Invert.Common

Check this out to  Assets/Plugins/uFrame/Invert.Common

#### uFrameKernel - Free Open Source
The core uFrame lifecycle system used on all uFrame Unity products.
https://github.com/InvertGames/uFrameKernel/tree/2.0
> **IMPORTANT** Make sure you install the 2.0 branch

Check this out to  Assets/Plugins/uFrame/uFrameKernel


#### uFrame.ECS - Free Open Source
https://github.com/InvertGames/uFrame.ECS
https://github.com/InvertGames/uFrame.ECS.git
Check this out to  Assets/Plugins/uFrame.ECS

#### UniRx - Free Open Source
You can use the full UniRx library from here:
https://github.com/neuecc/UniRx.git
Or use the bare essentials fork:
https://github.com/InvertGames/UniRx.git
Check this out to  Assets/Plugins/uFrame/UniRx
> Note: If installing the full version you might need to remove some folders.

#### Optional Code Generation Templates - Free Open Source
https://github.com/InvertGames/uFrame.ECS.Templates
Check this out to Assets/Plugins/Editor/uFrame.ECS.Templates
