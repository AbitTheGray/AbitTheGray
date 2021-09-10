# Abit Gray

Welcome!

I am full-time software programmer and free-time game prototype and engine programmer.

Living in Prague, Czech Republic (Central Europe).


## Social Links

- LinkedIn: https://www.linkedin.com/in/david-erben-6ba814164/
- Website: https://www.graymadness.net/ (Work-In-Progress)
- Discord: https://discord.gg/ejShm4Z
- Twitch: https://www.twitch.tv/graymadness


## Dreams

- ~~Work as C++ Game Engine Programmer with some decision power (team leader?)~~
- ~~Lead development of `Alien vs Predator` game inspired by [Natural Selection 1](https://en.wikipedia.org/wiki/Natural_Selection_(video_game)) and [Quake 3 Arena](https://en.wikipedia.org/wiki/Quake_III_Arena)~~ (see `AvP Resettlement` in TODO list)


## Programming Languages

Favorite:
- Modern C++ ([C++20](https://en.cppreference.com/w/cpp/20), just as new as possible)
  - Mostly `std` but the technology behind should always be the same (you can change allocations by `std::vector` but it must always be continuous block of data)
  - `CLion` by JetBrains as IDE
- C# [7.3](https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-7-3) / [8.0](https://docs.microsoft.com/en-us/dotnet/csharp/whats-new/csharp-8), [.NET 4.8](https://en.wikipedia.org/wiki/.NET_Framework_version_history#.NET_Framework_4.8) + [.NET Core](https://en.wikipedia.org/wiki/.NET_Core)
  - `Rider` by JetBrains as IDE
    - `VisualStudio` by Microsoft (with `ReSharper` by JetBrains) is also an option
    - `MonoDevelop` used to be good but...

I also do other IT languages, not limited to programming (SQL, ~~JavaScript~~) and even have advanced knowledge HTML+CSS.
Using Delphi and T-SQL at work but use C++ (and sometimes C#) during my free time.

I prefer GIT for versioning, especially from [JetBrains](https://www.jetbrains.com/)' GUI or command line ([Bash](https://en.wikipedia.org/wiki/Bash_(Unix_shell)) on linux, [Git Bash](https://gitforwindows.org/) on Windows).

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

Most of those links will not work - repositories are private until some meaningful progress is made.

### [AWEngine](https://github.com/graymadness/AWEngine) with Vulkan Renderer
  - Custom Low-level C++ Game Engine
    - Designed to provide platform-independent API which can be bended to developer's will
  - Multiple components (parts) which may be used by output project
    - Packet networking, UI, Audio...
  - *This is my "pet project" as I can work on any part of it at any time*
    - I also use it as a sandbox when tinkering / drafting mechanism for EmberSky

### EmberSky
  - Voxel-base action game
  - Client + Realm of servers
  - *I do the server side of the project, low-level drafts and part of the core library*

### [Voxelite](https://github.com/voxelite/Voxelite)
  - 3D Voxel Customizable Game (Server-side mods)
  - Revived!
  - *As AWEngine is my "engine pet project", this is my "game pet project"*


## TODO List (Postponed) + Ideas
Postponed until... unknown

This is just a list to take projects from as the one above gets empty (hopefully).

### [Decay](https://github.com/AbitTheGray/Decay-Library)
  - GoldSrc (`Half-Life`, `Counter-Strike 1.6`) File (Map, Textures...) Parser Library
    - Remake of [BspLib](https://github.com/AbitTheGray/BspLib) with addition
    - May be extended by JavaScript version (for web usage)
  - AWEngine "runtime"
    - Use AWEngine to emulate (maybe even improve upon) `GoldSrc` engine
    - Probably not compatible with `Half-Life Deathmatch` and `Counter-Strike 1.6` but hopefully with working multiplayer

### Yautja Cosplay
  - [Arduino](https://www.arduino.cc/) / [ESP32](https://www.espressif.com/en/products/socs/esp32) / [Teensy](https://www.pjrc.com/teensy/)
  - 3D print + Clay + Silicone
  - Servo Animatronics
  - Thermal camera

### BSP Map Parser
  - Inspired by `Wolfenstein 3D`, `DOOM` and `Duke Nukem 3D`
  - Do more research into BSP login (also used in `Quake` and `GoldSrc`)
  - Somewhat parent project to `Decay Library`
  - May help with remastering those games

### SoulEater draft using AWEngine
  - Load data from Dark Souls 1 (Remaster or PtD?), Dark Souls 2 (SotFS) and Dark Souls 3
    - Only parse, not to provide the data = must own the game
  - Render with AWEngine
    - Will be perfect benchmark environment for the engine
      - "modern" PBO-like environment + gameplay
      - 3 different ages
    - Probably not the best engine
  - Use same controls (user input + responsiveness) for all 3 Souls games = smoth

### AvP Resettlement
  - Aliens, Marines, Predators
  - Big maps with AI characters (humans and aliens)
  - Inspired by
    - [Natural Selection 1](https://en.wikipedia.org/wiki/Natural_Selection_(video_game))
      - Xenomorph Queen able to switch to top-view to mark "points of interest"
  - Fast paced action
  - Custom character equipment and appearance
  - Modding tools
