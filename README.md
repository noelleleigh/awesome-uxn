# Awesome Uxn [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Curated list of awesome Uxn projects from the community.

The [Uxn](https://100r.co/site/uxn.html) ecosystem is a personal computing playground, created to host small tools and games, programmable in its own unique assembly language.

## Documentation

- [Varvara](https://wiki.xxiivv.com/site/varvara.html) - Technical documentation of the Varvara computer and a list of all its devices.
- [Uxntal](https://wiki.xxiivv.com/site/uxntal.html) - Uxntal language reference manual.
- [Uxntal opcode manual](https://wiki.xxiivv.com/site/uxntal_reference.html) - List of Uxntal opcodes and their effects.
- [Sprite format](https://wiki.xxiivv.com/site/chr_format.html) - `.chr` file format description.

## Tutorials

- [Compudanzas(html)](https://compudanzas.net/uxn_tutorial.html) - Beginner-friendly guide for programming the Varvara computer.
- [Compudanzas(video)](https://www.youtube.com/watch?v=LrNuq_JgaOA) - Beginner-friendly video workshop for the Varvara computer.
- [Learn Uxntal in Y minutes](https://learnxinyminutes.com/docs/uxntal/) - Quick Uxntal guide.
- [macOS installation](https://eli.li/2021/09/27/how-to-install-uxn-on-macos)
- [Windows installation](https://itch.io/t/1605965/a-quick-guide-to-running-this-software)
- [Android installation](https://llllllll.co/t/uxn-virtual-computer/46103/253) - Guide for running Uxn on the Android operating system through Termux.

## Emulators

* Desktop

  - [Uxnemu](https://git.sr.ht/~rabbits/uxn/tree/main/item/src/uxnemu.c) - The original implementation of the Uxn emulator.
  - [Uxncli](https://git.sr.ht/~rabbits/uxn/tree/main/item/src/uxncli.c) - Basic command-line interface version of Uxnemu.
  - [Uxn-lua](https://github.com/DeltaF1/uxn-lua) - A port of the Uxn instruction set and Varvara virtual computer to Lua and the [Love2D](https://love2d.org/) game engine.
  - [Libretro port](https://github.com/kivutar/uxn) - Implementation for the [Libretro](https://www.libretro.com/) emulation layer.
  - [Webuxn](https://github.com/aduros/webuxn) - Lightweight port of the Uxn virtual machine to the web via WebAssembly.
  - [EssenceOS](https://gitlab.com/nakst/essence/-/tree/master/ports/uxn) - An implementation for the [Essence](https://gitlab.com/nakst/essence) operating system.
  - [Varvara.jl](https://github.com/Ismael-VC/Varvara.jl) - Assembler and emulator for Uxn ported to Julia.
  - [Zabava](https://git.sr.ht/~ft/zabava) - Experimental implementation in Haskell.

* Other systems

  - [Game Boy Advance](https://git.badd10de.dev/uxngba/about/)
  - [Nintendo DS](https://github.com/asiekierka/uxnds)
  - [Playdate](https://git.sr.ht/~rabbits/uxn-playdate)
  - [Logisim](https://github.com/DeltaF1/uxn-logisim)
  - [PlayStation Vita](https://github.com/ivodopiviz/uxnvita)
  - [Raspberry Pi Pico](https://git.sr.ht/~alderwick/pico-uxn)
  - [Teletype](https://github.com/csboling/teluxn)
  - [ESP32](https://github.com/max22-/uxn-esp32)
  - [iOS](https://github.com/kylestew/UxniOS)
  - [STM32](https://github.com/kylestew/armuxn)
  - [STM32duino](https://github.com/cassvs/arduxno-demo)
  - [Rockbox](https://tilde.town/~nihilazo/varvara_rockbox.html)
  - [IBM PC](https://github.com/cr1901/pcuxn)

## Applications

* Creative

  - [Left](https://wiki.xxiivv.com/site/left.html) - Graphical plain-text editor with proportional fonts and Uxntal syntax highlighting.
  - [Nasu](https://wiki.xxiivv.com/site/nasu.html) - Spritesheet editor with the `.chr` format support.
  - [Noodle](https://wiki.xxiivv.com/site/noodle.html) - Illustration tool with animation capabilities.
  - [Orca](https://wiki.xxiivv.com/site/orca.html) - Livecoding IDE.

* Utilities

  - [Dexe](https://wiki.xxiivv.com/site/dexe.html) - Graphical hex editor.
  - [Calc](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/software/calc.tal) - Graphical hexadecimal calculator.
  - [Clock](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/examples/devices/datetime.tal) - Graphical clock.
  - [Oscean](https://github.com/XXIIVV/oscean/blob/main/src/oscean.tal) - Static site generator.

* Games

  - [Niju](https://hundredrabbits.itch.io/niju) - Hiragana and katakana learning game.
  - [Donsol](https://hundredrabbits.itch.io/donsol) - Card game about exploring a dungeon made of a standard 54 poker card set.
  - [Flappy](https://github.com/keijiro/uxn-sketches/blob/main/flappy.tal) - Implementation of a Flappy Bird-like game.
  - [Pong](https://compudanzas.net/uxn_tutorial_day_6.html) - Recreation of the classic Pong game.
  - [Snake](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/examples/demos/snake.tal) - Classic Snake game implementation.
  - [Cat Cubes](https://pup.town/catcubes.html) - Puzzle game about matching and clearing tiles from a board.

* Networking

  - [Xrxs](https://nilfm.cc/git/xrxs/about/) - Experimental game server using the Plan 9 protocol 9p.
  - [Uxnyap](https://github.com/klardotsh/uxnyap) - Helper binary for generic abstract networking.

* Operating systems

  - [Collapse OS](https://collapseos.org/download.html) - Experimental Uxn port of Collapse OS.

* Demos

  - [Bad-apple-uxn](https://github.com/karolbelina/bad-apple-uxn) - Bad Apple!! video on a single Uxn ROM.

## Development tools

* IDEs

  - [Learn-uxn](https://metasyn.github.io/learn-uxn/) - A web-based development environment with a text editor and up-to-date versions of Uxnasm and Uxnemu.

* Assemblers & compilers

  - [Uxnasm](https://git.sr.ht/~rabbits/uxn/tree/main/item/src/uxnasm.c) - The original implementation of the Uxntal assembler in about 400 lines of ANSI C.
  - [Asma](https://git.sr.ht/~rabbits/uxn/tree/main/item/projects/software/asma.tal) - Uxntal assembler written in Uxntal itself.
  - [Ruxnasm](https://github.com/karolbelina/ruxnasm) - Uxntal assembler focused on error reporting.
  - [Uxncle](https://github.com/CPunch/Uxncle) - Compiler for a small subset of C to Uxn bytecode.
  - [Pyuxncle](https://github.com/CPunch/Pyuxncle) - Python implementation of Uxncle.
  - [Conch](https://github.com/Armael/conch) - Compiler for a C-like language with Lisp-like syntax to Uxn bytecode.
  - [Uxn-ng](https://git.sr.ht/~tenshi/uxn-ng) - Uxntal assembler with bytecode annotating.
  - [Uxnbruteforce](https://github.com/max22-/uxnbruteforce) - Tool for optimizing little pieces of Uxntal code.
  - [Uxnlin](https://git.sr.ht/~rabbits/uxnlin) - Linter for Uxntal.
  - [Uxnbot](https://git.sr.ht/~alderwick/uxnbot) - IRC bot for assembling and running small Uxntal snippets.

* Uxntal language support

  - [Emacs mode](https://github.com/xaderfos/uxntal-mode)
  - [Emacs mode (alt)](https://github.com/rafapaezbas/uxntal-mode)
  - [Kakoune syntax](https://git.sr.ht/~athorp96/uxntal.kak)
  - [Micro syntax](https://nilfm.cc/git/dotfiles/tree/micro/syntax/uxn.yaml)
  - [Sublime syntax](https://git.sr.ht/~rabbits/uxn/tree/main/item/etc/tal.sublime-syntax)
  - [Vim plugin](https://github.com/karolbelina/uxntal.vim)
  - [Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=karolbelina.uxntal)

## Metadevelopment tools

* Testing

  - [Uxn-instruction-tests](https://github.com/DeltaF1/uxn-instruction-tests) - Test suite for the Uxn CPU instruction set.
  - [Uxntal-test-suite](https://github.com/karolbelina/uxntal-test-suite) - Test suite for Uxntal.

* Benchmarking

  - [Bunnymark](http://kira.solar/pub/bunnymark.txt) - Render performance benchmark.

## Community

- [Lines](https://llllllll.co/t/uxn-virtual-computer/46103)
- [#uxn on irc.esper.net](https://webchat.esper.net/?channels=uxn)
- [#uxn on Merveilles](https://merveilles.town/tags/uxn)
