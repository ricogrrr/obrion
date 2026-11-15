# Obrion - Free Roblox Lua/Luau Script Obfuscator

**[obrion.xyz](https://www.obrion.xyz)** is a free online obfuscator for Roblox
Lua and Luau scripts. Paste a script, get protected output back - no download,
no setup, no paywall.

## Why obfuscate?

Roblox scripts are delivered to the client as Lua bytecode. Anyone with an
executor can dump and read your source. Obfuscation doesn't make theft
impossible - nothing does - but it raises the cost from "copy-paste" to
"hours of manual deobfuscation work," which stops the vast majority of
script theft in practice.

## What it protects against

- Casual source reading via executors and script dumpers
- Copy-paste redistribution of your scripts
- Simple reverse-engineering of game logic, remotes, and algorithms

## Features

- Free, no account required to try it
- Lua and Luau compatible output - runs on Roblox and standard executors
- Browser-based: nothing to install
- Fast: obfuscation takes seconds

## Getting started

1. Open **[obrion.xyz](https://www.obrion.xyz)**
2. Paste your Lua/Luau script
3. Copy the obfuscated output and use it like the original

## Guides

- [What is Lua obfuscation?](https://www.obrion.xyz/guides/what-is-lua-obfuscation)
- [How to obfuscate a Roblox script](https://www.obrion.xyz/guides/how-to-obfuscate-a-roblox-script)
- [Protect your Roblox scripts](https://www.obrion.xyz/guides/protect-your-roblox-scripts)
- [Luau vs Lua](https://www.obrion.xyz/guides/luau-vs-lua)
- [Run obfuscated scripts on executors](https://www.obrion.xyz/guides/run-obfuscated-scripts-on-executors)
- [Free Lua obfuscator online](https://www.obrion.xyz/guides/free-lua-obfuscator-online)

## Links

- Website: https://www.obrion.xyz
- Security & disclosure: https://www.obrion.xyz/security
- Privacy: https://www.obrion.xyz/privacy

## Notes for developers

If you're building tooling around Roblox script protection, the
[guides](https://www.obrion.xyz/guides) cover the threat model
(executor-based dumping, bytecode inspection, why pure client-side
protection has limits) in depth.

*Obfuscation is defense-in-depth, not a guarantee. Pair it with
server-side validation for anything that matters.*
