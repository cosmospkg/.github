# 🌌 Cosmos Package System

**The package manager for when your distribution is on fire.**  
Minimal. Static. Offline-friendly. Powered by tarballs, TOML, and spite.

Cosmos is a package management ecosystem built for:
- Broken systems
- Custom distros
- Initramfs environments
- Recovery USBs
- People who’ve had `apt` fail them one too many times

It avoids dynamic linking, daemons, and unnecessary complexity. It prefers tools that still work when `/bin/sh` doesn’t.

## Core Repositories

- [`cosmos`](https://github.com/cosmospkg/cosmos) — Core CLI and package manager logic
- [`cosmos-docs`](https://github.com/cosmospkg/cosmos-docs) — Full documentation for Stars, Galaxies, Nova, and Stellar
- [`example-galaxy`](https://github.com/cosmospkg/example-galaxy) — Sample packages and Galaxy layout (works with `glibc`)

## Live Project Site

> [**https://cosmos-pkg.org**](https://cosmos-pkg.org)

Includes usage examples, full documentation, and design rationale.

## Philosophy

> No TLS. No Python. No Bash. Just packages.  
> Designed for mount points, minimalism, and malfunctioning systems.

If you can host it with `python3 -m http.server`, Cosmos can install from it.

## License

MIT. No CLA. No drama.

---
