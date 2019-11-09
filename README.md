# [Particle][] development platform for [PlatformIO][]

**This PlatformIO platform is not currently endorsed or supported
by either PlatformIO or Particle.**

Particle is an All-In-One Platform for Cellular and WiFi IoT devices.
For more information about Particle, see their website and [particle.io]().

# Usage

1. Install [PlatformIO][]
2. Create a PlatformIO project and configure a platform option in your
[platformio.ini][] file:

This platform is not yet part of platformio's registry, and as such,
you will need to use the url form of [platform version options][]
in your [platformio.ini][]

```ini
[env:particle]
platform = https://github.com/HackerHappyHour/platform-particle.git
board = ...
...
```

To use a specific branch or tag of this platform, (for example `dev`),
create a github based url accordingly. 

```ini
[env:particle-dev]
platform = https://github.com/HackerHappyHour/platform-particle.git#dev
board = ...
...
```

[Particle]: https://particle.io/iot-platform
[PlatformIO]: https://platformio.org
[platformio.ini]: https://docs.platformio.org/en/latest/projectconf.html
[platform version options]: https://docs.platformio.org/en/latest/projectconf/section_env_platform.html
