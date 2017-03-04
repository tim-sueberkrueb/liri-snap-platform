## Liri App Platform for Snap

Liri App Platform package for [snap][snapcraft-io]. This snap package
serves as bundle for libraries commonly used by Liri Apps.

### Dependencies
* [Ubuntu][ubuntu-com] == 16.04
  * Qt dependencies are currently tailored for 16.04
* [snapcraft][snapcraft-gh]

### Build
From the root of the repository, run:
```sh
snapcraft
```

### Install
From your build directory, run:
```sh
sudo snap install --dangerous liri-app-platform*.snap
```

### Try
To run the included [Fluid][fluid-gh] demo:
```sh
snap run liri-app-platform.fluid-demo
```

[ubuntu-com]: https://www.ubuntu.com/
[snapcraft-io]: https://snapcraft.io
[snapcraft-gh]: https://github.com/snapcore/snapcraft
[fluid-gh]: http://github.com/lirios/fluid
