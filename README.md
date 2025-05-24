# mib_lib

> Helpful systems and libraries for making Skript games, highly inspired by 1bardesign's `batteries`.

Get your servers off the ground faster! mib_lib fills out Skript’s feature set with useful systems, utilities for projects any size.
Easy to install, use, and to trim down for your project's needs.

> [!IMPORTANT]
>
> A lot of the modules **will fail to work** if you don't have the required addon list installed.
>  
> Please install the latest versions of the following addons:
>
> - [SkCheese](https://github.com/erenkarakal/SkCheese)
> - [oopsk](https://github.com/sovdeeth/oopsk)
> - [SkBee](https://modrinth.com/plugin/skbee)
> - [skript-reflect](https://github.com/TPGamesNL/skript-reflect)
> - [Skript](https://github.com/SkriptLang/Skript)
---

## 📦 Getting Started

### How do I use `that module`?

Examples are kept in the examples folder, Quick, practical scripts showing how to use each module.

### General usage

To find the functions, Use your editor’s **find-in-all** function *(shift+ctrl+f in vsc)* or just browse through the files.

> VSkript for VSCode also provides documentation formatting on hover, so I use this when using mib_lib. 

---

## 📖 FAQ

### Why no Skript Addon D:?
I wanted to keep this pure Skript so you can learn from the libraries and easily change whatever you want.

### Can I use only some modules?
Absolutely. Copy out what you need, or keep the full set for convenience, any dependencies will be listed at the top of the module, under the description.

### Why snake_case?
It's personal preference for me since I work in game engines that use this casing, it’s easier to read in skript files, in my opinion.

### Will any of my variables be overriden?
No, unless you already had variables under the "-mib_lib::" list, there will be no overriding / deleting of values

### Will this impact my performance?
This is a Skript library, so any performance impact will be *negligible*.
The **real** performance bottlenecks in Skript projects usually come from how systems are implemented,
not from libraries like this.
Every module in mib_lib has been carefully designed with both readability and efficiency in mind.

---

## 🎛️ Contributing

I aim to keep this approachable and beginner-friendly. PRs welcome for any improvements, or additions!

Raise an issue if something’s unclear, or message `mibers` on Discord.

---

## 🫀 (big) Inspiration:
 - Sovde's "skript-systems"
 - 1bardesign's "batteries"
