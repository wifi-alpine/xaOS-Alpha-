# xaOS
<p align="center">
  <img src="Sans titre 63_20260918183557.png" alt="xaOS Logo" width="500">
</p>
«A Linux distribution being redesigned from the ground up.»

is an experimental Linux operating system inspired by Artix Linux.

The current version uses an alias-based design, providing a consistent interface over existing Linux tools and components.

Current design

xaOS currently follows an Artix-inspired philosophy:

- 🐧 Linux-based
- ⚡ Lightweight
- 🧩 Modular
- 🔧 User-controlled
- 🚫 No systemd by default
- 🖥️ Custom user experience
- 🔗 Alias-based system commands

For example:

xa install firefox
xa remove firefox
xa update
xa search firefox

The aliases provide a simple interface while the underlying Linux tools remain accessible.

Inspired by Artix

xaOS takes inspiration from "Artix Linux" (https://artixlinux.org/), particularly its approach to:

- Alternative init systems
- Avoiding systemd
- Lightweight system design
- User control
- Arch Linux compatibility

xaOS is not intended to simply be a rebrand of Artix. Its goal is to develop its own tooling, conventions, defaults, and eventually its own architecture.

Future architecture

The current alias-based design is temporary.

One of the planned directions for xaOS is a declarative operating-system architecture.

Instead of manually building a filesystem, the user could describe the desired system:

directory "/system"
directory "/apps"
directory "/users"

package "firefox" -> "/apps/firefox"
package "kernel" -> "/system/kernel"

xaOS could then use this configuration to generate the filesystem and eventually a complete bootable system.

This is currently an experimental/future concept, not the architecture of the current release.

Status

🚧 Early development

xaOS is experimental. Its architecture, tools, package system, and user interface may change substantially.

Goals

- Keep Linux understandable
- Give users control over their system
- Avoid unnecessary complexity
- Provide a consistent command interface
- Build a genuinely modular operating system
- Experiment with new approaches to Linux system design
- DEBLOAT 🤤

---

xaOS — You are the OS

