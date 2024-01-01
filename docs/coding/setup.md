# Coding setup

I currently have two computers I use for coding. One is setup with Windows and has a latest-generation GPU (as of 2023), and the other has Linux (Debian + KDE). My Linux computer has no GPU and is much more portable, so I use it for everything except high performance computing and Windows-specific applications.

## Platform

I use Windows + WSL and Linux (Debian + KDE) interchangeably, depending on the circumstances. For my recent projects, I try to add cross-platform support, although this isn't always possible. Going forward, I plan to use Linux to develop any non-GPU applications, and Windows with either MinGW or WSL to develop GPU code.

## Editor

When editing code, I use [Visual Studio Code](https://code.visualstudio.com/). I also use [Neovim](https://neovim.io/) with [NVChad](https://nvchad.com/) occasionally, but I find it makes me less productive.

## Deployment

All of my code is published through [GitHub](https://www.github.com), and I use the command line to build and run all of my projects. Most of my projects have a Makefile and some unit tests, as well as documentation on how to build and run the project.

This website is hosted through [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages).

## Computer Specs

This is probably the least important aspect of my development environment, but I've chosen to include it for compatibility reasons.

### Linux Computer
- OS: Linux
- Distribution: Debian
- Desktop Environment: KDE Plasma
- Package Manager: Flatpak (preferred for graphical applications) or `apt`
- RAM: 16GB
- Internal Storage: 512GB SSD
- CPU: Intel i7 9th generaion

### Windows Computer
- OS: Windows 11
- Package Manager: Microsoft Store (preferred), `winget`, or none
- RAM: 32GB DDR5
- Internal Storage: 2TB SSD
- CPU: AMD Ryzen 9 6900
- GPU: AMD Radeon 6850
