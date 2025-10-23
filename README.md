![JellyCar logo](https://static.wikia.nocookie.net/jellycar/images/9/91/Jellycarlogo.png/revision/latest?cb=20231007222847)

## JellyCar is a great 2D game with soft body physics created by Walaber. 
https://twitter.com/walaber

This is homebrew version that I made with permission from original author for Windows.


Current implemetation uses my library: [Andromeda-Lib](https://github.com/DrakonPL/Andromeda-Lib)

## Build instructions.

### Important
For all platforms you must clone first 
[Andromeda-Lib](https://github.com/DrakonPL/Andromeda-Lib) , then this repository.

### PlayStation Vita

- Install newest VitaSDK using https://github.com/vitasdk/vdpm  
- Compile Androimeda-Lib
  - Go to Androimeda-Lib/Build/Vita 
  - Run "make -jn"  (where n is numer of cores of your cpu)
- Compile JellyCar
  - Go to JellyCar/Build/Vita
  - Run "make -jn"  (where n is numer of cores of your cpu)

### Nintendo Switch

- Install devkitpro with Nintendo Switch SDK
- Install additional libs
  - pacman -S switch-pkg-config switch-mesa switch-glad switch-glm switch-sdl2 switch-sdl2_mixer switch-freetype
- Compile JellyCar
  - Go to JellyCar/Build/Switch
  - Run "make -jn"  (where n is numer of cores of your cpu)
