# xaOS
<p align="center">
  <img src="Sans titre 63_20260918183557.png" alt="xaOS Logo" width="500">
</p>

A Linux distribution being redesigned from the ground up.
xaOS is an experimental Linux operating system built on a Debian foundation.
The current version uses an alias-based design, providing a consistent interface over existing Linux tools and components.

Current design:

Linux-based (Debian core)

Lightweight

Modular

User-controlled

Custom user experience

Alias-based system commands (e.g., xa-install, xa-update)
The aliases provide a simple interface while the underlying Linux tools remain accessible.

Future architecture (maybe in ver 1.0):
The current alias-based design is temporary.
One of the planned directions for xaOS is a declarative operating-system architecture.
Instead of manually building a filesystem, the user could describe the desired system:
directory "/system" directory "/apps" directory "/users"
package "firefox" -> "/apps/firefox" package "kernel" -> "/system/kernel"
xaOS could then use this configuration to generate the filesystem and eventually a complete bootable system.
This is currently an experimental/future concept, not the architecture of the current release.

Status:
Early development
xaOS is experimental. Its architecture, tools, package system, and user interface may change substantially.

Goals:

Keep Linux understandable

Give users control over their system

Avoid unnecessary complexity

Provide a consistent command interface

Build a genuinely modular operating system

Experiment with new approaches to Linux system design

DEBLOAT 🤤

---
xaOS — You are the OS!
