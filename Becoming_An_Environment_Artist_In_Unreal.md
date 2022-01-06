# Becoming an Environment Artist in Unreal

>## Table Of Contents

 - [Introduction to Environment Art](#introduction-to-environment-art)
 - [Department Interactions in Development](#department-interactions-in-development)
 - [Names and Terminology](#-names-and-terminology)
---
## Introduction to Environment Art

 -[TOC](#table-of-contents)

What you will learn
 - Terminology of environment art within game production and unreal
 - Folder structure and file naming
 - Importing meshes, textures and assets into unreal properly
 - Using the grid and planning with modular workflows
 - Texture settings, density and usage
 - Blockout meshes and understanding mesh footprints
 - Material creation
 - Collision setup
 - optimization
 - Lighting overview and lightmaps

Secions of this course
 - Section 1 - Pre-production
 - Section 2 - Tools in Unreal
 - Section 3 - Materials and Lighting

---
## Department Interactions in Development

 -[TOC](#table-of-contents)

- What responsibilities does an environment artist have
- The chain of command
- Steps from concept, art, design, level layout and QA
- Interacting with design for gameplay
- Working with different size teams

### Responsibilities of an Environment Artist
 
 - Creating props and assets
 - Creating textures
 - Creating materials
 - Work directly with design and level art to make levels and environments
 - Creating collisions, LODs, lightmaps for assets
 - Brainstorming and creating advanced blockout shapes and designs for level layout
 - Collaborating with other members to members to complete deadlines or sprints during production

### Game Environment Production

![GameEnvironmentProduction](images/GameEnvironmentProduction.png)

### Working With Designers

![WorkingWithDesigners](images/WorkingWithDesigners.png)

### Team Size

- AAA Studios / Larger Teams
  -- --
  Generally more specialized tasks, larger art team, more resources, slightly less learning of other disciplines, more focused tasking

- AA or Indie Studios / Midsize Teams
  -- --
  Broader tasks and assignments, less management and more creative control on tasks, mid to small size art team, less resources, lots of learning of other skills

- Start ups and Groups / small Size Teams
  -- --
  Working on multiple aspects out of environment art, typically not a lot of management, good for people that can self manage their time, requires a lot of self discipline, learn a lot of things that you would have never had a chance to try

---
## Names and Terminology

 -[TOC](#table-of-contents)

- Common terminology
- Environment Artist-based terminology
- Common topics/sayings and what they mean relative to development
- The right term for the right job - knowing what applies

### Common Terminology

These are terms or phrases used commonly throughout production by anyone in the game development cycle

They are shared among multiple groups, departments, or members of production team. Knowing these will help to inform you to understand better communication with groups other than your own.

  - Sprint / Production Cycle
  
    **How you might hear it** - "Let's keep focus on this task for this sprint and we will worry about that issue for nest sprint"

    **What it means** - Refers to taking a smaller portion or goal of the final production and working on it in chunks or smaller pieces to reach smaller goals that will eventually equate to the final larger ressults.

  - Pre Production / Prepro
    
    **How you might hear it** - "We have to figure out how this is going to work in pre production before we go into full production  on it"

    **What it means** - Refers to the period of time at the beginning of a project taht is meant for research, development, and testing to figure out how the project will run and work. This helps to ensure fewer issues later during full production with potentially new pipelines or processes.
  
  - Engine
    
    **How you might hear it** - "Let's get into the engine and see how it runs"

    **What it means** - Refers to the game engine used for development.

  - Build / The Buuild
    
    **How you might hear it** - "Have you got the lastest version of the build? It's looking much better than yesterday"

    **What it means** - The current version of the game or state of game that is currently being used and tested. Used when talking about what currently is included in the game. If you hear the term "Building" or "Cooking" the Build, it refers more to the construction or finalization of the current game for testing.

  - Bug
    
    **How you might hear it** - "This is a pretty major bug, we should get QA to check for this"

    **What it means** - Refers to a problem or issue that has occured within the game or some aspect of development that will need to be addressed or fixed.

  - Cert / Certification
    
    **How you might hear it** - "We have submitted the final build for certification"

    **What it means** - Refers to the poin in production that the game has been approved by console or game platform developers for final release.

### Environment Terminology

These are terms or phrases used commonly throughout production typically but not exclusively by environment artists.

They are not as commonly known in other departments or other team members. Knowing these will help to inform you to understand better communication with other environment artists. It's best to assume that other departments might not know what these terms mean.

  - Bakes / Baked Down
    
    **How you might hear it** - "This is looking great for your high poly - let's go ahead and move on to get it baked down"

    **What it means** - This generally refers to the reverse to the textures and the texturing process. Generally yused to define the creation of assets from the high to the low poly model or the combination of details on an asset combined and reduced to make for a more and optimized final result. This can also be referring to lighting when it is baked to texture maps from the light sources in engine.

  - Materials / Shaders / Mats
    
    **How you might hear it** - "We will need to use a glass shader on this portion of the model so we can see through it"

    **What it means** - These are terms used to describe materials that are applied to assets used in the game engine. Materials describe or display the visual properties of the asset.

  - Mesh / Geo / Geometry
    
    **How you might hear it** - "The geometry in the level is just placeholder for now"

    **What it means** - Thes are terms used to describe 3D model that is being used in  the engine or for produvtion. A mesh is derived of polygons to display a 3D visualization of a model.

  - Lightmap
    
    **How you might hear it** - "This mesh needs custom lightmaps"

    **What it means** - This is a texture that is generated and applied to assets in the engine that stimulate lighting that is baked/pre-rendered. This allows for lighting to be stimulated for cheaper than having dynamic or movaeble lighting information.

  - LOD
    
    **How you might hear it** - "I think we should push the LODs on the mesh in a bit more for performance"

    **What it means** - This is a abbrevation of the term **Level Of Detail**. Thsis is a optimized version of a mesh that is swapped in, in place of the original mesh to save on performance at a further distance from camera where heavy details are not as needed or essential for visual quality or gameplay.

  - MIPs / MIP maps
    
    **How you might hear it** - "The mipping on this alpha is causing it to get a bit blurry - lt's sharpen it some"

    **What it means** - Similar to LODs, this is an optimization term. This is a optimized and reduced size version of a texture that is swapped in, in place of the original texture to save on performance at a further distance from camera where heavy details are not as needed or essential for visual quality or gameplay.

  - Z-Fighting / Clipping
    
    **How you might hear it** - "We have some flickering going on between these two pieces of geometry, might be z-fighting"

    **What it means** - This is when two assets are so close together in X,Y or Z that they cut throught each other or fight for space visually on screen. Can often produce a flickering or error visually as the engine is confused as to which asset to display on top or instead of the other.

  - Culling
    
    **How you might hear it** - "Don't worry about that part of the scene, its being culled out from the main view here"

    **What it means** - This is where an asset that is not shown on screen is not rendered so to avoid rendering unnecessary assets and rsources to the player.

  - Blockout / Blocking / Graybox
    
    **How you might hear it** - "i've completed the first pass on the blockout and will be handling it over to art today"

    **What it means** - These are terms used to define creating a temporary placeholder asset or space in the environment to determine playability/gameplay mechanics/and general flow or look of a level. Many times a designer or level artist will blockout a environment space before the environment artist works on it.

  - Drawcalls / Draw Count
    
    **How you might hear it** - "The drawcalls in this area of the level are pretty high - let's see where we can optimize some here"

    **What it means** - In order to  render information (assets and materials) to screen, the GPU of your computer recieves a signal or drawcall as to how to render that asset. Each asset and material you have in your scene counts towards the total number of drawcalls needed to be sent to the GPU to be rendered correctly and in real time.

---