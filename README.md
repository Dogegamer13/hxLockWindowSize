# hxLockWindowSize

A small Haxe library that lets you **lock the window size** (disable resizing and moving) in desktop builds using [Lime](https://github.com/openfl/lime) / [OpenFL](https://github.com/openfl/openfl).

##  Features
- Prevents the user from resizing the game window
- Optionally prevents moving the window
- Designed for **Windows + hxcpp**
- Simple API, easy to integrate into any project

## Installation
Install from [Haxelib](https://lib.haxe.org/p/hxLockWindowSize):

```bash
haxelib install hxLockWindowSize

## HOW TO USE

1️⃣ **Import in your `Main.hx`**  
Place this at the top (or bottom) of your `Main.hx` file:

```haxe
import hxLockWindowSize.LockWindowSize;

# Originally a fork of [hxWindowColorMode](https://github.com/TBar09/hxWindowColorMode-main)
