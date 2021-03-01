# Abit Gray

Welcome!

I am full-time software programmer and free-time game prototype and engine programmer.

Living in Prague, Czech Republic (Central Europe).


## Social Links

- LinkedIn: https://www.linkedin.com/in/david-erben-6ba814164/
- Website: https://www.graymadness.net/
- Discord: https://discord.gg/ejShm4Z
- Twitch: https://www.twitch.tv/graymadness


## Programming Languages

Favorite:
- Modern C++ ([C++20](https://en.cppreference.com/w/cpp/20))
- C# [7.3](https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-7-3), [.NET 4.8](https://en.wikipedia.org/wiki/.NET_Framework_version_history#.NET_Framework_4.8) + [.NET Core](https://en.wikipedia.org/wiki/.NET_Core)

I also do other IT languages, not limited to programming (SQL, JavaScript) and even have advanced knowledge HTML+CSS.
Using Delphi and T-SQL at work but use C++ (and sometimes C#) at my free time.

I prefer GIT for versioning, especially from [JetBrains](https://www.jetbrains.com/)' GUI or console ([Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) on linux, [Git Bash](https://gitforwindows.org/) on Windows).

I am paying for [JetBrains All Products Pack](https://www.jetbrains.com/all/) myself, and I really like it! (not paid promotion)


## Templates

- [C++](https://github.com/AbitTheGray/Cpp-Template)
- ~~[C++ with LUA scripting](https://github.com/AbitTheGray/Cpp-LUA-Template)~~
- [C++ with Vulkan API](https://github.com/AbitTheGray/Cpp-Vulkan-Template)

Those are my repository templates to simplify prototyping (and motivate me to separate projects into smaller parts).
They contain basic CMake project structure and Github Actions (Linux + Windows).


## Fizz-Buzz
Based on [Fizz buzz](https://en.wikipedia.org/wiki/Fizz_buzz) game, those are my language showcase projects.

- [C++](https://github.com/AbitTheGray/Fizz-Buzz-cpp)
- [C#](https://github.com/AbitTheGray/Fizz-Buzz)


## TODO List

There used to be more bullet points with "deadlines" but lately I am running out of time.
Therefore, I went through the list and cleared it.

- [AWEngine](https://github.com/graymadness/AWEngine) with Vulkan Renderer
  - Custom Low-level C++ Game Engine
    - Designed to provide platform-independent API which can be bended to developer's will
  - Multiple components (parts) which may be used by output project
    - Packet networking, UI, Audio...
  - *This is my "pet project" as I can work on any part of it at any time*
    - I also use it as a sandbox when tinkering / drafting mechanism for EmberSky

- EmberSky
  - Voxel-base action game
  - Client + Realm of servers
  - *I do the server side of the project (and low-level drafts)*

Postponed until... unknown

- [Decay](https://github.com/AbitTheGray/Decay-Library)
  - GoldSrc (`Half-Life`, `Counter-Strike 1.6`) File (Map, Textures...) Parser Library
    - Remake of [BspLib](https://github.com/AbitTheGray/BspLib) with addition
    - May be extended by JavaScript version (for web usage)
  - AWEngine "runtime"
    - Use AWEngine to emulate (maybe even improve upon) `GoldSrc` engine
    - Probably not compatible with `Half-Life Deathmatch` and `Counter-Strike 1.6` but hopefully with working multiplayer

- BSP Map Parser
  - Inspired by `Wolfenstein 3D`, `DOOM` and `Duke Nukem 3D`
  - Do more research into BSP login (also used in `Quake` and `GoldSrc`)
  - Somewhat parent project to `Decay Library`
  - May help with remastering those games

- SoulEater draft using AWEngine
  - Load data from Dark Souls 1 (Remaster or PtD?), Dark Souls 2 (SotFS) and Dark Souls 3
    - Only parse, not to provide the data = must own the game
  - Render with AWEngine
    - Will be perfect benchmark environment for the engine
      - "modern" PBO-like environment + gameplay
      - 3 different ages
  - Use same controls (user input + responsiveness) for all 3 Souls games

- [Voxelite](https://github.com/voxelite/Voxelite)
  - 3D Voxel Customizable Game (Server-side mods)
  - I consider this project dead
    - Some ideas are re-used in Ember Sky
    - It was mainly learning project
