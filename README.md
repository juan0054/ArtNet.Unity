# ArtNet.Unity

ArtNet library for Unity(C#).

Forked from https://github.com/MikeCodesDotNET/ArtNet.Net

Receive and Send DMX512 via ArtNet.

![anim](anim.gif)

![photo](photo.jpg)

## Usage

### Send DMX

```csharp
DMXController controller;
int universe;
byte[] dmxData;
//512 channels

controller.Send(universe, dmxData);
```

---

# ArtNet.Net

An ArtNet library for C# and VB.Net developers. Based on the [Architecture for Control Networks (ACN)](http://acn.codeplex.com) project codebase

## Key Differences

* Removed RDM
* Removed all code unrelated to ArtNet

## Sample Projects

* C# Console app
* VB.Net Console app

https://www.reddit.com/r/Unity3D/comments/b1nwzz/simulated_volumetric_club_lighting_with_realtime/




Trent Robertson

I modeled a night club I used to frequent as a sketchpad for lighting simulations. The popular LED matrix animation software Jinx (left) streams pixel data via ArtNet to Unity (right)
https://www.youtube.com/watch?v=V-Ffo7ybThU
