# Sample-AssaultCube

This is a sample project demonstrating a basic H6AC integration in a game.  AssaultCube is an open-source game that we've patched to add H6AC support.

Here's a non-exhaustive list of major changes:
[server.cpp:4429](https://github.com/H6NTechnologies/Sample-AssaultCube/blob/master/source/src/server.cpp#L4429)
[client.cpp:88](https://github.com/H6NTechnologies/Sample-AssaultCube/blob/master/source/src/client.cpp#L88)


Nearly all patches have been marked with:
```
    /* -- Begin H6N patch -- */
    ...
    /* -- End H6N patch -- */
```

Note that you'll need H6AC binaries (H6Agent.dll, etc) to actually run the demo, which we have not provided.

Everything below this line is the original AssaultCube readme.


------------


## What is AssaultCube?
AssaultCube is a **FREE**, multiplayer, first-person shooter game, based on the
[CUBE engine](http://cubeengine.com/cube.php4).

Taking place in realistic environments, with fast, arcade gameplay,
it's addictive and fun!

With efficient bandwidth usage, it's low-latency and can even run over a 56 Kbps
connection. It's tiny too, weighing in at a lightweight about 50 MB package
available for [Windows](https://github.com/assaultcube/AC/releases/download/v1.2.0.2/AssaultCube_v1.2.0.2.exe), [Mac](https://github.com/assaultcube/AC/releases/download/v1.2.0.2/AssaultCube_v1.2.0.2.dmg) and [Linux](https://github.com/assaultcube/AC/releases/download/v1.2.0.2/AssaultCube_v1.2.0.2.tar.bz2). On the correct settings, it can even run
on old hardware (Pentium III and above).

## Features in a nutshell:

 * It's **FREE**.
 * Source code is available under a zlib-like open source license.
 * Low latency, it can even run across a 56 Kbps connection!
 * Lightweight size, only about 50 MB to download, plus additional maps
 average 20 KB each!
 * With the correct settings, it can run on old hardware
 (Pentium III and above).
 * Officially runs on most major systems (Windows: 2000/XP/Vista/7/8/10, Linux,
 Mac OS X: 10.4+), and maybe even some
 [non-major ones](http://assault.cubers.net/docs/getstarted.html)?
 * Has a built in, in-game map editor to help players create their own maps and
 allows for co-operative editmode in realtime with others!
 * Features a single-player bot system.
 * Supports recording of your game by the "demo" system.
 * Contains many multiplayer game modes, including: Deathmatch, Survivor,
 Capture the Flag, Hunt the Flag, Keep the Flag, Pistol Frenzy, Last Swiss
 Standing & One-Shot One-Kill (plus team versions of these modes).
 * Comes pre-packaged with several dozen different maps!

## More info:

Most of this README was directly copied from the
[AssaultCube Homepage](http://assault.cubers.net/), which should have everything
you need in relation to AssaultCube.

## Redistribution:

You may redistribute AssaultCube in any way the license permits, such as the
free unmodified distribution of AssaultCube's source and binaries. If you have
any doubts, you can look at the
[license](http://assault.cubers.net/docs/license.html).

