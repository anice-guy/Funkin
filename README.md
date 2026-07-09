# Friday Night Funkin: Placeholder Engine
An FNF' engine(?) made out of boredom  
Based out of Funkin v0.2.7.1  

Play the original game one here: https://www.newgrounds.com/portal/view/770371  
Support Funkin' on their itch.io page: https://ninja-muffin24.itch.io/funkin  

## Credits

### Placeholder Engine
- [angg](https://x.com/anicer_guy) - Main Dev  
... that's it

### Funkin' Crew
- [ninjamuffin99](https://x.com/ninja_muffin99) - Programmer
- [PhantomArcade3K](https://x.com/phantomarcade3k) and [Evilsk8r](https://x.com/evilsk8r) - Art
- [Kawaisprite](https://x.com/kawaisprite) - Musician

## Build instructions

### Prerequisetes
First, you'll need to [get Haxe](https://haxe.org/download/) and [get HaxeFlixel](https://haxeflixel.com/documentation/install-haxeflixel/), you might probably already have these if you're bothering to read this guide  
To compile for Windows you will need MSVC and the Windows SDK, you can get these by installing [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/), but do NOT choose the desktop c++ workload or whatever its called, it includes a bunch of shit youll never use  
instead, install both components i mentioned earlier individually  

it's also possible to install these components WITHOUT the need of the full Visual Studio IDE, but i wont go into detail (vaguepost king)  
if you wanna figure it out, search "visual studio build tools" on google or other search engine if youre weird.

For linux and mac Uhhhh Idk LMao sorrey  

### Making the videoGame
To compile for your current OS run:
```bash
lime build cpp
```

To compile and run do:
```bash
lime test cpp
```

You can also append the `-debug` flag to compile a debug build
also do `-verbose` for more info on the compiling process
