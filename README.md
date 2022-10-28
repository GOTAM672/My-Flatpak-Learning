# My-Flatpak-Learning

## prerequisite

1. First setup your linux distro from [here](https://flatpak.org/setup/) according to your distro.

2. Then install flatpak builder 
```bash
flatpak install flathub org.flatpak.Builder
```

## To Install a runtime and the matching SDK

Flatpak requires every app to specify a runtime that it uses for its basic dependencies. Each runtime has a matching SDK (Software Development Kit), which contains all the things that are in the runtime, plus headers and development tools

```bash
flatpak install flathub org.freedesktop.Platform//21.08 org.freedesktop.Sdk//21.08
```
