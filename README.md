<!--lint disable no-dead-urls-->

<p align="center"><img src="media/awesome-v-logo.svg" width="400"/></p>

# Awesome V with stars

> A curated list of awesome V frameworks, libraries, software and resources.

[V](https://vlang.io/) is a simple, fast, safe, compiled language for developing maintainable software.

## Contents

* [Applications](#applications)
  * [Build Systems](#build-systems)
  * [Command-line](#command-line)
  * [Editors](#editors)
  * [Games](#games)
  * [Graphics](#graphics)
  * [Interpreters/Compilers](#interpreterscompilers)
  * [Operating systems/Kernels](#operating-systemskernels)
  * [Package managers](#package-managers)
  * [Project management](#project-management)
  * [Serialization](#serialization)
  * [Utilities](#utilities)
  * [Web](#web)
* [Libraries](#libraries)
  * [Audio](#audio)
  * [Automation](#automation)
  * [Command line interface (CLI) / Terminal / Shell](#command-line-interface-cli--terminal--shell)
  * [Database clients](#database-clients)
  * [Discord](#discord)
  * [Eventing](#eventing)
  * [File handling](#file-handling)
  * [Game development](#game-development)
  * [Graphics](#graphics-1)
  * [Interoperability](#interoperability)
  * [IRC](#irc)
  * [Networking](#networking)
  * [Operating system](#operating-system)
  * [Scientific computing](#scientific-computing)
  * [Serial Communications](#serial-communications)
  * [Telecommunications](#telecommunications)
  * [Telegram](#telegram)
  * [Text processing](#text-processing)
  * [User Interface toolkits](#user-interface-toolkits)
  * [Utility](#utility)
  * [Web](#web-1)
* [Other](#other)
  * [Articles](#articles)
  * [Books](#books)
  * [Communities](#communities)
  * [Editor plugins](#editor-plugins)
  * [Forums](#forums)
  * [GitHub Actions](#github-actions)
  * [GitHub templates](#github-templates)
  * [IDEs with V](#ides-with-v)
  * [Online IDEs with V](#online-ides-with-v)
  * [Operating Systems & OS Development Examples](#operating-systems--os-development-examples)
  * [Patterns](#patterns)
  * [Programming contests](#programming-contests)
  * [Syntax highlighting](#syntax-highlighting)
  * [Tutorials](#tutorials)
  * [Videos](#videos)
  * [Contributors](#contributors)

## Applications

### Build Systems

* [vab](https://github.com/vlang/vab) ⭐ 346 | 🐛 8 | 🌐 V | 📅 2026-04-30 - The official V tool to build and package applications for Android.
* [clockwork](https://github.com/emmathemartian/clockwork) ⭐ 26 | 🐛 0 | 🌐 V | 📅 2025-09-19 - A language-agnostic build tool wrote in V.
* [vab-sdl](https://github.com/larpon/vab-sdl) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2026-01-04 - Standalone and extra command for `vab` to build and package
  SDL2 and SDL3 based applications importing `vlang/sdl`.

### Command-line

* [lsv](https://github.com/mike-ward/lsv) ⭐ 73 | 🐛 2 | 🌐 V | 📅 2026-02-25 - `ls` file lister in the spirit of exa, eza, lsd, pls, natls, ls-go and others.
* [crepl](https://github.com/l1mey112/crepl) ⭐ 35 | 🐛 0 | 🌐 V | 📅 2024-02-05 - Compile and execute C code on the fly as you type it.
* [pfjson](https://github.com/fleximus/pfjson) ⭐ 31 | 🐛 0 | 🌐 V | 📅 2026-06-13 - A CLI tool to convert OpenBSD Packet Filter configuration files (`pf.conf`) to JSON and vice versa.
* [vqrcode](https://github.com/carlosqsilva/vqrcode) ⭐ 30 | 🐛 0 | 🌐 V | 📅 2025-10-01 - CLI for creating QR Codes.
* [vast](https://github.com/lydiandy/vast) ⭐ 29 | 🐛 0 | 🌐 V | 📅 2021-09-17 - A simple tool for vlang, generate v source file to AST json file.
* [vzcc](https://github.com/malisipi/vzcc) ⚠️ Archived - A CLI cross-compiling tool based on Zig CC for V.
* [runner](https://github.com/Naheel-Azawy/runner) ⭐ 28 | 🐛 1 | 🌐 V | 📅 2024-06-22 - A tool that automates running/compiling code written in various programming languages.
* [HN-top](https://github.com/BafS/hn-top) ⭐ 24 | 🐛 0 | 🌐 V | 📅 2020-03-30 - A simple command to list most recent news from hacker-news.
* [vlsh](https://github.com/vlshcc/vlsh) ⭐ 23 | 🐛 0 | 🌐 V | 📅 2026-04-17 - \*nix Shell written in V (pipes, plugins, mux mode, etc).
* [klonol](https://github.com/hungrybluedev/klonol) ⭐ 20 | 🐛 2 | 🌐 V | 📅 2026-06-29 - CLI tool to help you "clone all" Git repositories belonging to you. Works with GitHub and Gitea.
* [vfetch](https://github.com/carlosqsilva/vfetch) ⭐ 17 | 🐛 1 | 🌐 V | 📅 2026-04-21 - A macOS system information fetch written in V.
* [vLogQL](https://github.com/lmangani/vLogQL) ⭐ 17 | 🐛 0 | 🌐 V | 📅 2024-03-14 - A tiny command-line utility to query LogQL APIs.
* [vinit](https://github.com/pranavbaburaj/vinit) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2021-05-26 - A tool to generate v projects.
* [v\_llama\_cpp](https://github.com/sakana-ctf/v_llama_cpp) ⭐ 15 | 🐛 0 | 🌐 V | 📅 2026-06-17 - Lightweight V wrapper for Llama.cpp, enabling efficient LLM execution.
* [portctl](https://github.com/apoprotsky/portctl) ⭐ 13 | 🐛 0 | 🌐 V | 📅 2026-01-20 - CLI tool to manage Docker Swarm resources using Portainer API.
* [vin](https://github.com/DeoDorqnt387/vin) ⚠️ Archived - A Basic Command Line Interface for V.
* [symlinker](https://github.com/serkonda7/symlinker) ⚠️ Archived - A small Linux tool to manage symlinks.
* [vfc](https://github.com/Ict00/vfc) ⭐ 9 | 🐛 0 | 🌐 V | 📅 2026-03-09 - A simple TUI file manager, made with V.
* [vgoogle](https://github.com/changhz/vgoogle) ⭐ 9 | 🐛 0 | 🌐 V | 📅 2025-09-22 - Make google search on the terminal.
* [vsqlite](https://github.com/quaesitor-scientiam/vsqlite) ⭐ 9 | 🐛 2 | 🌐 V | 📅 2026-03-28 - SQLite CLI and module replacement written in pure V.
* [fdup](https://github.com/gechandesu/fdup) ⭐ 8 | 🐛 0 | 🌐 V | 📅 2025-09-24 - Find and remove duplicate files.
* [github-releases](https://github.com/Dracks/repo-download-asset) ⭐ 8 | 🐛 1 | 🌐 V | 📅 2023-05-06 - Cli tool to keep track of applications released as GitHub Release (or assets in workflow) and download them.
* [minimax-v](https://github.com/whiter001/minimax-v) ⭐ 8 | 🐛 0 | 🌐 V | 📅 2026-07-13 - Local AI Agent runtime implemented in the V language.
* [verve](https://github.com/MohammadMD1383/verve) ⭐ 7 | 🐛 0 | 🌐 V | 📅 2022-11-16 - Simple and fast static file server.
* [dnshammer](https://github.com/tailsmails/dnshammer) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2026-08-12 - A covert communication channel that encodes data into DNS cache timing differences.
* [stripshot](https://github.com/tailsmails/stripshot) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2026-08-12 - Strips device/OS fingerprints from screenshots.
* [netprint](https://github.com/tailsmails/netprint) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2026-08-16 - A low-level network telemetry and anomaly detection tool designed to identify environmental changes and traffic interception.
* [v-terminal-apps](https://github.com/cogrow4/V-Terminal-Apps) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2025-11-02 - A collection of high-quality terminal applications written in V, including job planner, calculator, notes, file browser, quiz game, budget tracker, P2P chat (WIP), and Pomodoro timer.
* [envelop](https://github.com/tailsmails/envelop) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2026-08-17 - Generates background HTTP HEAD requests to obfuscate real web traffic.
* [lagger](https://github.com/tailsmails/lagger) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2026-08-10 - A dynamic network latency and packet loss simulation proxy designed to emulate real-world network degradation at the application layer.
* [mushroomtek](https://github.com/tailsmails/mushroomtek) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2026-08-16 - Don't worry about the grid, you are just a radius (Anti-IMSI catcher/Anti-Triangulation...).
* [newfolder](https://github.com/tailsmails/newfolder) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2026-08-02 - A lightweight, high-performance command-line steganography, file obfuscation, and secure metadata-destruction workstation written in V.
* [PhoneSnatchProof](https://github.com/tailsmails/PhoneSnatchProof) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2026-08-11 - An FS that encrypts your app data and keeps them on RAM (with a backup).
* [sockslender](https://github.com/tailsmails/sockslender) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2026-08-16 - A lightweight, blazing-fast SOCKS5 proxy failover tool written in V.
* [zilch](https://github.com/mike-ward/zilch) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2025-11-27 - An entertaining and amusing simulation of an installer.
* [amdim](https://github.com/tailsmails/amdim) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-07-11 - Make your screen dimmer than 0%.
* [fastgit](https://github.com/tailsmails/fastgit) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-08-17 - A command-line tool written in V, designed to automate and simplify uploading, syncing, and modifying GitHub repositories.
* [httest](https://github.com/gechandesu/httest) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-08-03 - A CGI-enabled HTTP test server for mocking backends, inspecting requests and simulating latency and failures.
* [musicc](https://github.com/tailsmails/musicc) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-08-13 - A lightweight, high-performance command-line music compiler.
* [oscall](https://github.com/tailsmails/oscall) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-08-18 - A native, low-level CLI utility written in V for inspecting, loading, and dynamically executing arbitrary C/C++ functions.
* [salty](https://github.com/tailsmails/salty) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-08-12 - A lightweight command-line utility written in V for secure data encryption, deep compression, and steganographic-like format obfuscation.
* [timingless](https://github.com/tailsmails/timingless) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-08-13 - A SOCKS5 proxy that sits between your applications and Tor, enforcing constant bandwidth to defeat traffic timing analysis.
* [vcli](https://github.com/changhz/vcli) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2023-07-10 - A CLI tool to generate folder structure according to the [guideline](https://blog.vlang.io/the-complete-beginners-guide-to-cli-apps-in-v/)
* [vspect](https://github.com/zakuro9715/vspect) ⚠️ Archived - A tool to inspect vlang source file. ( Archived )
* [gatevay](https://github.com/tailsmails/gatevay) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-08-14 - A lightweight, multi-gateway SOCKS5 proxy tool.
* [pixviper](https://github.com/tailsmails/pixviper) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-08-12 - A parallel template matching and de-redaction investigation tool written in V.
* [vtrace](https://github.com/tailsmails/vtrace) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-08-14 - An automated execution tracer and step-by-step source code instrumenter for the V programming language.
* [waterjail](https://github.com/tailsmails/waterjail) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-08-15 - A lightweight, surgical Seccomp-BPF dynamic sandboxing and analysis tool written in V.
* [anyside](https://github.com/tailsmails/anyside) ⭐ 0 | 🐛 0 | 🌐 V | 📅 2026-07-11 - Transport-Agnostic Covert Tunneling Sandbox & Protocol Gateway.
* [vin32](https://github.com/tailsmails/vin32) ⭐ 0 | 🐛 0 | 🌐 V | 📅 2026-08-10 - A basic, heuristic-based CLI tool to generate V language bindings from simple Windows C header files.
* [vsnap](https://github.com/skandhas/vsnap) ⭐ 0 | 🐛 0 | 🌐 V | 📅 2026-07-07 - A tiny local snapshot tool for saving and restoring files before risky edits, lighter than Git and built around explicit paths.

### Editors

* [text\_editor](https://github.com/vlang/v/blob/master/examples/term.ui/text_editor.v) ⭐ 37,797 | 🐛 86 | 🌐 V | 📅 2026-08-18 - Small text editor from the official V examples.
* [ved](https://github.com/vlang/ved) ⭐ 1,476 | 🐛 34 | 🌐 V | 📅 2026-02-15 - 1 MB text editor written in V with hardware accelerated text rendering. Compiles in <1s.
* [lilly](https://github.com/tauraamui/lilly) ⭐ 461 | 🐛 10 | 🌐 V | 📅 2026-08-17 - TUI editor and VIM/Neovim alternative.
* [vPDF](https://github.com/vlang/pdf) ⭐ 84 | 🐛 0 | 🌐 V | 📅 2023-12-19 - A module to simplify PDF file creation using the V programming language.
* [vee](https://github.com/Larpon/vee) ⭐ 60 | 🐛 1 | 🌐 V | 📅 2025-05-24 - V Editor Engine. A V module providing the guts of a text editor. Comes with a [TUI editor example](https://github.com/Larpon/vee/blob/master/examples/tuieditor/) ⭐ 60 | 🐛 1 | 🌐 V | 📅 2025-05-24.
* [volt](https://github.com/Volt-Editor-Team/volt) ⭐ 19 | 🐛 5 | 🌐 V | 📅 2026-07-06 - Aims to be a fully featured text editor written entirely in Vlang.
* [polygon-editor](https://github.com/ArtemkaKun/polygon-editor) ⚠️ Archived - A tool to create and edit 2D polygons with sprite lookup, created in V.
* [vro](https://github.com/undivisible/vro) ⭐ 5 | 🐛 2 | 🌐 V | 📅 2026-08-10 - <0.5MB micro-inspired basic text editor. Compatible with Micro's YAML syntax highlighting.

### Games

* [flappylearning-v](https://github.com/vlang/v/tree/master/examples/flappylearning) ⭐ 37,797 | 🐛 86 | 🌐 V | 📅 2026-08-18 - A simple flappy learning demo in v.
* [Boundstone](https://github.com/organization/boundstone) ⭐ 62 | 🐛 3 | 🌐 V | 📅 2020-05-10 - High Performance / Fast Compilation / Lightweight Minecraft: Bedrock Edition Server.
* [Kurarin](https://github.com/FireRedz/kurarin) ⭐ 54 | 🐛 1 | 🌐 C | 📅 2026-05-30 - osu! beatmap visualizer made in V. [Example video](https://p153.p0.n0.cdn.getcloudapp.com/items/6quvQjb5/ce3ea737-eb29-4b8c-a5f3-65a804a2f56f.mp4).
* [minesweeper](https://github.com/ali-furkan/minesweeper-v) ⭐ 39 | 🐛 0 | 🌐 V | 📅 2026-01-30 - A simple Minesweeper game written in vlang.
* [vchess](https://github.com/hedgeg0d/vchess) ⭐ 18 | 🐛 0 | 🌐 V | 📅 2026-06-12 - Chess game written in V programming language.
* [Puzzle Vibes](https://github.com/Larpon/puzzle_vibes) ⭐ 16 | 🐛 0 | 🌐 V | 📅 2026-05-18 - A jigsaw-like puzzle game written in V using `shy`.
* [v-pong](https://github.com/thebigsmileXD/v-pong) ⚠️ Archived - A classic paddle game brought back to life through the power of V.
* [Dino](https://github.com/egevtech/dino) ⭐ 0 | 🐛 0 | 🌐 V | 📅 2026-08-14 - A simple console arcade game written in V where you control a dino and avoid cactuses and birds.

### Graphics

* [vpaint](https://github.com/pisaiah/vpaint) ⭐ 87 | 🐛 2 | 🌐 V | 📅 2026-01-17 - MS-Paint alternative written in V.
* [vRayTracer](https://github.com/ali-raheem/vraytracer) ⭐ 51 | 🐛 1 | 🌐 V | 📅 2020-06-28 - A simple ray tracer written in V.
* [mpv-v](https://github.com/xjunko/mpv-v) ⭐ 32 | 🐛 0 | 🌐 V | 📅 2024-07-08 - World's Simplest Video Player.

### Interpreters/Compilers

* [v](https://github.com/vlang/v) ⭐ 37,797 | 🐛 86 | 🌐 V | 📅 2026-08-18 - The language V itself. Simple, fast, safe, compiled language for developing maintainable software.
* [cotowali](https://github.com/cotowali/cotowali) ⚠️ Archived - A statically typed scripting language that transpiles into POSIX sh.
* [vas](https://github.com/v420v/vas) ⭐ 111 | 🐛 24 | 🌐 V | 📅 2026-08-01 - A simple x86-64 assembler written in V.
* [vcc](https://github.com/lemoncmd/vcc) ⭐ 110 | 🐛 0 | 🌐 V | 📅 2024-03-05 - A C compiler written in V.
* [Aixt](https://github.com/fermarsan/aixt) ⭐ 90 | 🐛 0 | 🌐 V | 📅 2026-07-30 - Programming framework for microcontrollers based on a V-based language and written in V.
* [stas](https://github.com/l1mey112/stas/tree/0.1.0-v-compiler) ⚠️ Archived - A stack based compiled programming language. The bootstrap compiler is written in V.
* [papyrus-compiler](https://github.com/russo-2025/papyrus-compiler) ⭐ 55 | 🐛 5 | 🌐 V | 📅 2026-06-12 - Open-source compiler for Bethesda's Papyrus scripting language (Skyrim SE/AE).
* [monkey\_v](https://github.com/Delta456/monkey_v) ⭐ 44 | 🐛 0 | 🌐 V | 📅 2026-08-14 - Implementation of [Thorsten Ball's Monkey Language](https://interpreterbook.com/) in V.
* [Vork](https://github.com/Itay2805/Vork) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2019-11-24 - Alternative V compiler/interpreter written in Python.
* [vbf](https://github.com/vpervenditti/vbf) ⭐ 20 | 🐛 0 | 🌐 V | 📅 2021-06-02 - A brainfuck interpreter/compiler.

### Operating systems/Kernels

* [Vinix](https://github.com/vlang/vinix) ⭐ 2,163 | 🐛 24 | 🌐 V | 📅 2026-06-18 - Small and simple OS in V. Runs bash.
* [V-Unikernel](https://github.com/vlang/unikernel) ⭐ 22 | 🐛 1 | 🌐 V | 📅 2024-10-20 - A unikernel is a computer program statically linked with the operating system code on which it depends.

### Package managers

* [vpm](https://github.com/vlang/vpm) ⭐ 132 | 🐛 36 | 🌐 V | 📅 2026-04-25 - The V language package management tool written in V.

### Project management

* [vset](https://github.com/mulh8377/vset) ⭐ 20 | 🐛 0 | 🌐 Shell | 📅 2020-02-07 - A project setup and configuration tool for V projects.
* [Lenra template](https://github.com/lenra-io/template-v) ⭐ 3 | 🐛 2 | 🌐 V | 📅 2023-02-13 - The Lenra template to write V app for Lenra platform.

### Serialization

* [vproto](https://github.com/emily33901/vproto) ⭐ 56 | 🐛 1 | 🌐 V | 📅 2022-09-24 - Protobuf compiler and runtime in V.
* [vlang-yaml](https://github.com/jdonnerstag/vlang-yaml) ⭐ 28 | 🐛 2 | 🌐 V | 📅 2022-04-19 - A V-native YAML reader, incl. YAML-to-JSON converter.
* [vgura](https://github.com/gura-conf/vgura) ⭐ 21 | 🐛 1 | 🌐 V | 📅 2023-09-19 - Official Gura parser for V.
* [maple](https://github.com/emmathemartian/maple) ⭐ 10 | 🐛 0 | 🌐 V | 📅 2025-12-16 - A very simple key-value config format wrote in V.
* [v-toxml](https://github.com/radare/v-toxml) ⭐ 9 | 🐛 0 | 🌐 V | 📅 2021-02-25 - XML Serialization library for V.
* [ini-v](https://github.com/ldedev/ini-v) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2026-06-12 - Simple and practical module for manipulating ini/cfg file.

### Utilities

* [qptorrent](https://github.com/qptorrent/qptorrent) ⭐ 36 | 🐛 0 | 🌐 V | 📅 2026-02-25 - A minimal GUI/CLI BitTorrent client written in V + vlang/gui.
* [emoji-mart-desktop](https://github.com/ttytm/emoji-mart-desktop) ⭐ 24 | 🐛 0 | 🌐 V | 📅 2024-05-26 - An emoji picker created with V, webview and SvelteKit.
* [v-nodejs-addon](https://github.com/fanlia/v-nodejs-addon) ⭐ 7 | 🐛 0 | 🌐 Coq | 📅 2024-01-15 - An demo of how to create a Node.js addon with V.
* [boj-server](https://github.com/hyperpolymath/boj-server) ⭐ 3 | 🐛 16 | 🌐 JavaScript | 📅 2026-08-18 - Unified developer tool server using V for the network adapter layer. Exposes REST (port 7700), gRPC (7701), and GraphQL (7702) from a single V codebase. 18 capability cartridges loaded via Zig FFI with Idris2-verified interfaces.
* [raur](https://github.com/Matejsdevelopment/raur) ⭐ 2 | 🐛 0 | 🌐 V | 📅 2026-06-10 - Simple Arch User Repository (AUR) helper coded in Vlang.
* [unix-emulators-win](https://github.com/Ddiidev/unix-emulators-win) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-07-02 - Collection of 16 UNIX utilities rewritten in V for Windows.

### Web

* [Gitly](https://github.com/vlang/gitly) ⭐ 1,477 | 🐛 32 | 🌐 V | 📅 2026-07-11 - A light and fast SCM alternative to GitHub/GitLab written in V.
* [vorum](https://github.com/vlang/vorum) ⭐ 224 | 🐛 8 | 🌐 V | 📅 2024-11-10 - Open-source blogging/forum software written in V.
* [Vebview.JS](https://github.com/malisipi/Vebview.JS) ⭐ 84 | 🐛 0 | 🌐 V | 📅 2025-10-06 - Electron/Neutralino.JS alternative written in V.
* [Mantis](https://github.com/khalyomede/mantis) ⭐ 44 | 🐛 6 | 🌐 V | 📅 2026-07-13 - A web framework written in V.
* [vss](https://github.com/vssio/vss) ⚠️ Archived - Easy-to-use static site generator.
* [vblog](https://github.com/scurty-labs/vblog) ⭐ 28 | 🐛 0 | 🌐 V | 📅 2023-12-20 - A simple, fast and responsive blogging system.
* [vico\_bot](https://github.com/KArjmand/vico_bot) ⭐ 19 | 🐛 0 | 🌐 V | 📅 2026-02-24 - Lightweight self-hosted AI chatbot with persistent memory and tool calling.
* [VTik](https://github.com/Sharqo78/VTik) ⚠️ Archived - TikTok and Twitter video downloader app (CLI / Telegram Bot).
* [Tiniest Veb Server](https://github.com/davlgd/tVeb) ⭐ 17 | 🐛 0 | 🌐 V | 📅 2024-09-29 - A < 1MB static hosting web server written in V, based on `veb`. 🍃
* [v-admin-skeleton](https://github.com/xiusin/v-system-skeleton) ⭐ 15 | 🐛 0 | 🌐 Vue | 📅 2024-07-28 - Backend skeleton written in V.
* [Vieter](https://github.com/ChewingBever/vieter) ⭐ 11 | 🐛 0 | 🌐 V | 📅 2023-07-17 - Arch Linux repository server & package build system, written in V.
* [Vlang Benchmarks Visualization](https://github.com/ArtemkaKun/VlangBenchmarksVisualization) ⚠️ Archived - Fancy statistics and plots for *[Is V still fast?](https://fast.vlang.io/)*.
* [gitval](https://github.com/davlgd/gitval) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2026-01-15 - A static site generator for Git repositories, written in V.
* [v-vite starter](https://github.com/v-vite/starter) ⭐ 6 | 🐛 0 | 🌐 CSS | 📅 2025-11-20 - A starter kit for Veb applications, preconfigured with Vite.js.
* [Mustela](https://github.com/filipos800/mustela) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-06-20 - Ultra-high-performance static site generator (SSG) engineered for speed (>9,000 pages/sec) and total data sovereignty.
* [Heroku Buildpack for V](https://github.com/zztkm/heroku-buildpack-v) ⭐ 2 | 🐛 1 | 🌐 Shell | 📅 2022-04-22 - Deploy V apps on Heroku.
* [rr-dl](https://github.com/dy-tea/rr-dl) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2025-04-10 - Royal-Road Novel downloader.
* [Verne](https://github.com/davlgd/Verne) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-05-11 - The other static site generator named after a famous French author.
* [highlighter](https://codeberg.org/tamer/highlighter) - Inject syntax highlighting into HTML files at build time, or via the CLI tool.

## Libraries

### Audio

* [miniaudio](https://github.com/larpon/miniaudio) ⭐ 54 | 🐛 2 | 🌐 C | 📅 2025-07-06 - Bindings for the excellent miniaudio C audio library.
* [vspeech](https://github.com/thecodrr/vspeech) ⭐ 50 | 🐛 1 | 🌐 V | 📅 2020-01-15 - Complete V bindings for Mozilla's DeepSpeech TensorFlow based Speech-to-Text library. 📢📜
* [vave](https://github.com/thecodrr/vave) ⭐ 40 | 🐛 1 | 🌐 V | 📅 2024-06-15 - A crazy simple library for reading/writing WAV files in V. 🌊

### Automation

* [vrobot](https://github.com/eioo/vrobot) ⭐ 53 | 🐛 2 | 🌐 V | 📅 2022-05-13 - Desktop automation for V. Only supports Windows.
* [v-webdriver](https://github.com/quaesitor-scientiam/v-webdriver) ⭐ 20 | 🐛 0 | 🌐 V | 📅 2026-07-22 - A V language implementation of the W3C WebDriver protocol for browser automation.

### Command line interface (CLI) / Terminal / Shell

* [boxx](https://github.com/thecodrr/boxx) ⭐ 105 | 🐛 0 | 🌐 V | 📅 2023-03-01 - Create highly customizable terminal boxes that also look great! 📦
* [bartender](https://github.com/tobealive/bartender) ⭐ 52 | 🐛 1 | 🌐 V | 📅 2024-11-26 - Customizable progress indicators for V terminal applications.
* [termtable](https://github.com/serkonda7/termtable) ⚠️ Archived - V Terminal Tables: Simple and highly customizable library to display tables in the terminal.
* [vargs](https://github.com/nedpals/vargs) ⚠️ Archived - V library for parsing arguments from argv-like arrays. ( Archived )
* [progressbar](https://github.com/Waqar144/progressbar) ⭐ 31 | 🐛 0 | 🌐 V | 📅 2023-03-14 - An easy to use V library for creating progress bars in cli.
* [spinners](https://github.com/rhygg/spinners) ⭐ 22 | 🐛 2 | 🌐 V | 📅 2022-10-22 - Create spinners in your terminal!
* [lol](https://github.com/0xLeif/lol) ⭐ 17 | 🐛 0 | 🌐 V | 📅 2022-07-21 - V version of lolcat (text/character rainbowizer).
* [vesseract](https://github.com/barrack-obama/vesseract) ⭐ 17 | 🐛 1 | 🌐 V | 📅 2021-11-14 - V wrapper for Tesseract-OCR (optical character recognition).

### Database clients

<!-- lint disable awesome-spell-check -->

* [redis](https://github.com/patrickpissurno/vredis) ⭐ 70 | 🐛 5 | 🌐 V | 📅 2024-03-22 - A Redis client for V, written in V.
* [mongodb](https://github.com/vlang/mongo) ⭐ 53 | 🐛 5 | 🌐 V | 📅 2024-09-06 - A MongoDB driver for V.
* [vduckdb](https://github.com/rodabt/vduckdb) ⭐ 47 | 🐛 0 | 🌐 V | 📅 2026-02-11 - A DuckDB client wrapper for V.
* [vsql](https://github.com/lydiandy/vsql) ⭐ 47 | 🐛 1 | 🌐 V | 📅 2021-10-21 - A sql query builder for V.
* [vmemcached](https://github.com/blacktrub/vmemcached) ⭐ 12 | 🐛 0 | 🌐 V | 📅 2021-02-21 - Memcached client for V, written in V.
* [vredis](https://github.com/xiusin/vredis) ⭐ 10 | 🐛 0 | 🌐 V | 📅 2026-06-26 - A simple, user-friendly, and comprehensive Redis client.
* [redict](https://github.com/einar-hjortdal/redict) ⭐ 8 | 🐛 0 | 🌐 V | 📅 2026-08-03 - Client for Redict, a LGPL-3.0-only fork of Redis (compatible with Redis <=7.2.4).
* [firebird](https://github.com/einar-hjortdal/firebird) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2026-08-10 - Client for Firebird SQL.

### Discord

* [discord.v](https://github.com/Terisback/discord.v) ⚠️ Archived - User-friendly Discord bot library.
* [viscord](https://github.com/vlang/viscord) ⭐ 23 | 🐛 1 | 🌐 V | 📅 2020-10-22 - Pretty basic library for connecting to the Discord gateway.
* [kitten](https://github.com/geniushq/kitten) ⭐ 14 | 🐛 0 | 🌐 V | 📅 2026-02-11 - Simple Discord API library for writing bots.
* [vord](https://github.com/9xN/vord) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2022-04-01 - Library for interacting with user account endpoints and gateway (Self-bots, custom clients, etc).
* [discordwebhook](https://github.com/ysdragon/discordwebhook) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2023-09-11 - Super simple interface to send discord messages through webhooks.

### Eventing

* [eventbus](https://github.com/vlang/v/tree/master/vlib/eventbus) ⭐ 37,797 | 🐛 86 | 🌐 V | 📅 2026-08-18 - A simple event bus system for V.
* [rxv](https://github.com/ulises-jeremias/rxv) ⭐ 16 | 🐛 31 | 🌐 V | 📅 2026-08-07 - Reactive Extensions for the V language. Compose async event streams with creation, filtering, transformation, aggregation, timing, and combination operators.

### File handling

* [vmon](https://github.com/Larpon/vmon) ⭐ 39 | 🐛 2 | 🌐 C | 📅 2024-10-13 - Asynchronously watch for file changes in a directory. The module is essentially a V wrapper for `septag/dmon`. It works for Windows, macOS and Linux.
* [v-mime](https://github.com/nedpals/v-mime) ⭐ 25 | 🐛 0 | 🌐 V | 📅 2019-12-28 - MIME detection library for V.

### Game development

* [raylib.v](https://github.com/irishgreencitrus/raylib.v) ⭐ 69 | 🐛 12 | 🌐 C | 📅 2024-01-28 - Updated V bindings for [raylib](https://www.raylib.com) with plans for complete cross-platform support.
* [shy](https://github.com/Larpon/shy) ⭐ 63 | 🐛 2 | 🌐 C | 📅 2026-05-18 - A foundation that helps you being creative in V.
* [vraylib](https://github.com/MajorHard/vraylib) ⭐ 49 | 🐛 1 | 🌐 V | 📅 2021-04-28 - V wrapper (bindings) for raylib, the C game development framework.
* [engine](https://github.com/LouisSchmieder/engine) ⭐ 45 | 🐛 0 | 🌐 V | 📅 2022-02-16 - WIP Vulkan in V.
* [sdl2test](https://github.com/nsauzede/sdl2test) ⭐ 21 | 🐛 4 | 🌐 V | 📅 2026-04-14 - Exhaustive suite of tests and examples for SDL2 with V.
* [V\_ecs](https://github.com/mohamedLT/V_ecs) ⭐ 19 | 🐛 1 | 🌐 V | 📅 2023-04-07 - ECS library made in V inspired by Bevy ECS.
* [wren](https://github.com/larpon/wren) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2024-08-21 - V wrapper around the excellent Wren scripting language.
* [vraylib](https://github.com/mohamedLT/vraylib) ⭐ 7 | 🐛 4 | 🌐 V | 📅 2022-09-21 - A V wrapper for the awesome raylib library.
* [chipmunk2d](https://github.com/larpon/chipmunk2d) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2025-12-18 - V wrapper of the Chipmunk2D physics library.

### Graphics

* [vsl.vcl](https://github.com/vlang/vsl/tree/main/vcl#readme) ⭐ 401 | 🐛 35 | 🌐 V | 📅 2026-07-26 - VCL is a high level way of writing programs with OpenCL using V. These are highly opinionated OpenCL bindings for V. It tries to make GPU computing easy, with some sugar abstraction, V's concurrency and channels.
* [vsl.plot](https://github.com/vlang/vsl/tree/main/plot#readme) ⭐ 401 | 🐛 35 | 🌐 V | 📅 2026-07-26 - Plotting module for VSL with 85+ examples. Create line charts, scatter plots, 3D surfaces, bar charts, box plots, histograms, heatmaps, and more.
* [sdl](https://github.com/vlang/sdl) ⭐ 107 | 🐛 7 | 🌐 V | 📅 2026-02-02 - Official SDL2 & SDL3 bindings for V.
* [vsdl2](https://github.com/nsauzede/vsdl2) ⭐ 48 | 🐛 3 | 🌐 V | 📅 2026-05-23 - A libSDL2 wrapper.
* [viup](https://github.com/kjlaw89/viup) ⭐ 45 | 🐛 2 | 🌐 HTML | 📅 2024-01-05 - V wrapper for the C-based cross-platform UI library, IUP.
* [vglyph](https://github.com/vlang/vglyph) ⭐ 28 | 🐛 0 | 🌐 V | 📅 2026-07-07 - High-performance text rendering engine for the V programming language, built on Pango, FreeType, and Sokol.
* [V Earcut](https://github.com/Larpon/earcut) ⭐ 15 | 🐛 0 | 🌐 V | 📅 2025-12-18 - fast (real-time) polygon triangulation library based on [mapbox/Earcut](https://github.com/mapbox/earcut) ⭐ 2,575 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-02 to handle holes, twisted polygons, degeneracies and self-intersections.
* [vqoi](https://github.com/Le0Developer/vqoi) ⭐ 15 | 🐛 1 | 🌐 V | 📅 2023-07-18 - V: QOI - The "Quite OK Image" format for fast, lossless image compression.
* [vsdl](https://github.com/kjlaw89/vsdl) ⭐ 13 | 🐛 1 | 🌐 C | 📅 2022-01-11 - V wrapper for the C-based SDL library.
* [sgldraw](https://github.com/larpon/sgldraw) ⭐ 11 | 🐛 0 | 🌐 V | 📅 2025-02-18 - An experimental real-time vector render V module based on `sokol.sgl`.
* [svgg](https://github.com/Avocadocs/svgg) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2025-11-07 - V module to load and resterize svg file into `gg.Image` object.
* [V\_sokol\_gp](https://github.com/mohamedLT/V_sokol_gp) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2022-09-20 - A V wrapper for the sokol\_gp library for easy and fast 2d graphics.
* [vbmp](https://github.com/dy-tea/vbmp) ⭐ 2 | 🐛 0 | 🌐 V | 📅 2025-01-10 - Read and write bitmap files.
* [voronoi](https://github.com/larpon/voronoi) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2025-12-18 - V wrapper of [JCash/voronoi](https://github.com/JCash/voronoi) ⭐ 728 | 🐛 1 | 🌐 C | 📅 2026-07-25.

### Interoperability

* [jni](https://github.com/larpon/jni) ⭐ 29 | 🐛 1 | 🌐 V | 📅 2025-04-09 - V wrapper around the C Java Native Interface (Desktop + Android).
* [vphp](https://github.com/guweigang/vphp) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2026-07-25 - Vlang library for building PHP extensions natively in Vlang.
* [vjsx](https://github.com/guweigang/vjsx) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-08-10 - V bindings to quickjs javascript engine. Run JS in V.

### IRC

* [vitric](https://github.com/m-242/vitric) ⭐ 5 | 🐛 1 | 🌐 V | 📅 2022-08-24 - A transparent IRC library.

### Networking

* [vibe](https://github.com/tobealive/vibe) ⭐ 42 | 🐛 1 | 🌐 V | 📅 2024-11-15 - Request library that wraps libcurl to enable fast and reliable requests while providing a higher-level API.
* [vmq](https://github.com/jordan-bonecutter/vmq) ⭐ 24 | 🐛 0 | 🌐 V | 📅 2025-02-06 -  V wrapper For [ZMQ](https://zeromq.org/) (aka ZeroMQ, ØMQ, 0MQ: a high-performance asynchronous messaging library).
* [netaddr](https://github.com/gechandesu/netaddr) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2026-05-01 - IPv4, IPv6 and MAC (EUI-48, EUI-64) addresses manipulation library.
* [netio](https://github.com/gechandesu/netio) ⭐ 4 | 🐛 2 | 🌐 V | 📅 2026-07-31 - Low-level networking library for V that gives more control over sockets.
* [netr](https://github.com/tailsmails/netr) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-07-14 - A modular, zero-dependency raw socket and network packet crafting library written in V.

### Operating system

* [clipboard](https://github.com/vlang/v/tree/master/vlib/clipboard) ⭐ 37,797 | 🐛 86 | 🌐 V | 📅 2026-08-18 - V module for interacting with the OS clipboard. Fully cross-platform.
* [vlipboard](https://github.com/asvvvad/vlipboard) ⭐ 12 | 🐛 0 | 🌐 V | 📅 2020-07-25 - An easy to use wrapper of clipboard with Wayland and Termux support.
* [mmap](https://github.com/jdonnerstag/vlang-mmap) ⭐ 7 | 🐛 0 | 🌐 V | 📅 2021-06-21 - Provide native V-lang support for memory-mapping on Linux and Windows.
* [winreg](https://github.com/ldedev/WindowsRegistry) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2024-01-31 - MS Windows Registry API. (WIP)
* [rgc](https://github.com/tailsmails/rgc) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-07-17 - A lightweight, concurrent resource garbage collector for V.
* [vcomp](https://github.com/tailsmails/vcomp) ⭐ 0 | 🐛 0 | 🌐 V | 📅 2026-07-25 - A lightweight Linux Seccomp (Secure Computing Mode) BPF filter wrapper for vlang.

### Scientific computing

* [vsl](https://github.com/vlang/vsl) ⭐ 401 | 🐛 35 | 🌐 V | 📅 2026-07-26 - A Scientific Library with a great variety of different modules. Although most modules offer pure-V definitions, it also provides modules that wrap known C libraries among other backends that allow high performance computing as an alternative. Also provides opinionated wrappers for OpenBLAS, LAPACKE, MPI, OpenCL among other libraries.
* [vsl.fft](https://github.com/vlang/vsl/tree/main/fft#readme) ⭐ 401 | 🐛 35 | 🌐 V | 📅 2026-07-26 - Fast Fourier Transform module for VSL. Includes real and complex FFT with multiple backend options.
* [vsl.ml](https://github.com/vlang/vsl/tree/main/ml#readme) ⭐ 401 | 🐛 35 | 🌐 V | 📅 2026-07-26 - Machine Learning module for VSL with K-means, KNN, linear/logistic regression, SVM, decision trees, random forest, and more.
* [vsl.quaternion](https://github.com/vlang/vsl/tree/main/quaternion#readme) ⭐ 401 | 🐛 35 | 🌐 V | 📅 2026-07-26 - Quaternion math module for VSL. Supports 3D rotations, spherical linear interpolation (slerp), and Julia fractal generation.
* [vtl](https://github.com/vlang/vtl) ⭐ 166 | 🐛 26 | 🌐 V | 📅 2026-07-16 - The V Tensor Library is a numerical computing library supporting n-dimensional data structure, backed by VSL.
* [vtl.autograd](https://github.com/vlang/vtl/tree/main/autograd#readme) ⭐ 166 | 🐛 26 | 🌐 V | 📅 2026-07-16 - Automatic differentiation module for VTL. Enables gradient computation for machine learning and optimization.
* [vtl.datasets](https://github.com/vlang/vtl/tree/main/datasets#readme) ⭐ 166 | 🐛 26 | 🌐 V | 📅 2026-07-16 - Datasets module for VTL providing built-in datasets for ML benchmarking and tutorials.
* [vtl.nn](https://github.com/vlang/vtl/tree/main/nn#readme) ⭐ 166 | 🐛 26 | 🌐 V | 📅 2026-07-16 - Neural Networks module for VTL. Build and train deep learning models with layers, activations, and optimizers.
* [NeuralNetworks-V-Module](https://github.com/Eliyaan/NeuralNetworks-V-Module) ⭐ 30 | 🐛 0 | 🌐 V | 📅 2025-08-15 - This is a V module to create neural networks.
* [vplot](https://github.com/erdetn/vplot) ⭐ 16 | 🐛 0 | 🌐 C | 📅 2022-09-27 - V wrapper for GNU Plot (`gnuplot_i`).
* [vstats](https://github.com/rodabt/vstats) ⭐ 5 | 🐛 1 | 🌐 V | 📅 2026-08-18 - A dependency-free Linear Algebra, Statistics, and Machine Learning library written from scratch in V.
* [vnm](https://github.com/tailsmails/vnm) ⭐ 2 | 🐛 0 | 🌐 V | 📅 2026-08-10 - A minimalist, compiled neural network library written in the V programming language.

### Serial Communications

* [vi2c](https://github.com/erdetn/vi2c) ⭐ 14 | 🐛 0 | 🌐 V | 📅 2024-05-15 - A tiny (wrapper) library for I2C serial communication for Linux written in V.
* [vserialx](https://github.com/erdetn/vserialx) ⭐ 13 | 🐛 2 | 🌐 V | 📅 2024-07-29 - A tiny (wrapper) serial communication library for Linux written in V.
* [vserialport](https://github.com/erdetn/vserialport) ⭐ 11 | 🐛 0 | 🌐 V | 📅 2021-11-21 - V wrapper for [libserialport](https://sigrok.org/wiki/Libserialport).

### Telecommunications

* [vagi](https://github.com/Ouri028/vagi) ⭐ 7 | 🐛 0 | 🌐 V | 📅 2022-06-21 - Asterisk FastAGI library in V.

### Telegram

* [vgram](https://github.com/dariotarantini/vgram) ⭐ 150 | 🐛 0 | 🌐 V | 📅 2026-06-17 - Telegram bot library.
* [velegram](https://github.com/tailsmails/velegram) ⭐ 3 | 🐛 0 | 🌐 V | 📅 2026-07-14 - A V language wrapper for TDLib (Telegram Database Library).

### Text processing

* [crayon](https://github.com/thecodrr/crayon) ⭐ 61 | 🐛 2 | 🌐 V | 📅 2024-02-02 - Paint your terminal output like Picasso. 🖍️🎨
* [whisker](https://github.com/hungrybluedev/whisker) ⭐ 39 | 🐛 0 | 🌐 V | 📅 2024-06-16 - Fast, robust template engine for V inspired by mustache.
* [xlsx](https://github.com/hungrybluedev/xlsx) ⭐ 30 | 🐛 3 | 🌐 V | 📅 2026-06-29 - V library for reading and writing Microsoft Excel files.
* [chalk](https://github.com/etienne-napoleone/chalk) ⭐ 24 | 🐛 0 | 🌐 V | 📅 2022-07-29 - Colorize strings in the terminal.
* [cjson](https://github.com/lydiandy/cjson) ⭐ 15 | 🐛 0 | 🌐 V | 📅 2022-07-08 - Wrap cJSON for vlang.
* [v-regex](https://github.com/spytheman/v-regex) ⚠️ Archived - A simple regex library for V.
* [ascii\_robot](https://github.com/Delta456/ascii_robot) ⭐ 13 | 🐛 0 | 🌐 Coq | 📅 2020-09-28 - ASCII Robot generator written in V.
* [iconv](https://github.com/fanlia/iconv) ⭐ 7 | 🐛 0 | 🌐 V | 📅 2021-07-23 - Wrap iconv for vlang.
* [text-processing](https://github.com/ArtemkaKun/text-processing) ⚠️ Archived - V text processing library, that contains common tools to manipulate text data.
* [pcre2](https://github.com/srackham/pcre2) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2023-12-02 - Library for processing PCRE regular expressions.
* [Rosie-RPL](https://github.com/jdonnerstag/vlang-rosie) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2022-03-09 - A Rosie Pattern Language (RPL) implementation.
* [vsoup](https://github.com/marcalc/vsoup) ⭐ 6 | 🐛 0 | 🌐 V | 📅 2026-07-03 - A fast, JSoup-inspired HTML5 parser and DOM manipulation library for V, powered by Lexbor.
* [lexical\_uuid](https://github.com/einar-hjortdal/lexical_uuid) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2026-01-29 - Lexicographically-sortable universally unique identifiers.
* [slugify](https://github.com/einar-hjortdal/slugify) ⭐ 3 | 🐛 1 | 🌐 V | 📅 2025-12-17 - Transform Unicode strings to url-friendly human-readable ASCII slugs.
* [read\_xlsx\_v](https://github.com/fanlia/read_xlsx_v) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2023-07-15 - Read xlsx using vlang.
* [vxml](https://github.com/i582/vxml) ⭐ 1 | 🐛 0 | 📅 2022-12-08 - Pure V library for parsing XML to a DOM.

### User Interface toolkits

* [V UI](https://github.com/vlang/ui) ⭐ 2,511 | 🐛 116 | 🌐 V | 📅 2026-05-04 - Integrated cross platform UI toolkit for Windows, macOS, Linux, Android, iOS and the web.
* [iUI](https://github.com/isaiahpatton/ui) ⭐ 157 | 🐛 9 | 🌐 C | 📅 2026-07-30 - Isaiah's cross-platform GUI library for V. Inspired by the syntax of Java's Swing.
* [V-WebUI](https://github.com/webui-dev/v-webui) ⭐ 128 | 🐛 7 | 🌐 V | 📅 2026-03-20 - A wrapper for WebUI. A lightweight library that allows you to use any web browser as a GUI, with V in the backend and HTML5 in the frontend.
* [mui](https://github.com/malisipi/mui) ⭐ 111 | 🐛 10 | 🌐 V | 📅 2024-08-18 - A Cross-Platform UI library for Windows, Linux, Android and Web.
* [webview](https://github.com/ttytm/webview) ⭐ 83 | 🐛 5 | 🌐 V | 📅 2024-12-02 - Bindings for webview. A tiny library to build modern cross-platform GUI applications. It allows to combine V with modern web technologies to design a graphical user interface.
* [vgtk3](https://github.com/vgtk/vgtk3) ⭐ 64 | 🐛 3 | 🌐 V | 📅 2022-11-07 - A wrapper for GTK3 in V.
* [vig](https://github.com/nsauzede/vig) ⭐ 54 | 🐛 5 | 🌐 C | 📅 2024-02-19 - Bindings for [Dear ImGui](https://github.com/ocornut/imgui) ⭐ 75,704 | 🐛 1,234 | 🌐 C++ | 📅 2026-08-18 GUI toolkit.
* [vnk](https://github.com/nsauzede/vnk) ⭐ 54 | 🐛 0 | 🌐 V | 📅 2024-09-17 - Bindings for [Nuklear](https://github.com/vurtun/nuklear) ⚠️ Archived GUI toolkit.
* [bobatea](https://github.com/tauraamui/bobatea) ⭐ 24 | 🐛 0 | 🌐 V | 📅 2026-06-06 - TUI framework inspired by Bubble Tea.

### Utility

* [VInstall](https://github.com/malisipi/VInstall) ⭐ 45 | 🐛 2 | 🌐 V | 📅 2024-06-07 - A cross-platform installer creator.
* [vdotenv](https://github.com/zztkm/vdotenv) ⭐ 44 | 🐛 4 | 🌐 V | 📅 2024-08-11 - Support for .env files which loads environment variables.
* [dialog](https://github.com/ttytm/dialog) ⭐ 34 | 🐛 0 | 🌐 V | 📅 2024-10-17 - A cross-platform utility library to open system dialogs - open files, message boxes, color-pickers etc.
* [range](https://github.com/Delta456/range) ⭐ 34 | 🐛 0 | 🌐 V | 📅 2023-03-19 - Functionality of Python's range() in V.
* [json2v](https://github.com/ldedev/Json2V) ⭐ 32 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-11 - Convert a json to a struct in Vlang.
* [votp](https://github.com/OdaiGH/votp) ⭐ 19 | 🐛 0 | 🌐 V | 📅 2023-11-16 - TOTP and HOTP implementation in v.
* [vaker](https://github.com/ChAoSUnItY/vaker) ⭐ 18 | 🐛 0 | 🌐 V | 📅 2023-09-06 - A light-weight compile-time-generated data faker written in V.
* [objc](https://github.com/magic003/objc) ⭐ 11 | 🐛 0 | 🌐 V | 📅 2024-07-12 - V bindings to Objective-C runtime.
* [V-crypto](https://github.com/bstnbuck/V-crypto) ⭐ 5 | 🐛 0 | 🌐 V | 📅 2026-08-01 - Implementation of additional cryptographic algorithms.
* [dotenv](https://github.com/einar-hjortdal/dotenv) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2025-12-17 - Loads environment variables from a .env file for development purposes.
* [vhs](https://github.com/KevinDaSilvaS/vhs) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2024-04-14 - Haskell prelude list functions(zip, zipwith, head, etc) implemented in V.
* [structlog](https://github.com/gechandesu/structlog) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-05-02 - Structured logs library for V.
* [vanadium](https://github.com/tailsmails/vanadium) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-07-26 - Ada-level runtime safety for the V programming language.
* [vop](https://github.com/tailsmails/vop) ⭐ 0 | 🐛 0 | 🌐 V | 📅 2026-07-16 - A message-passing object protocol providing dynamic property management and closure-based state encapsulation.

### Web

* [veb](https://github.com/vlang/v/tree/master/vlib/veb) ⭐ 37,797 | 🐛 86 | 🌐 V | 📅 2026-08-18 - V's built-in web framework.
* [vex](https://github.com/nedpals/vex) ⭐ 342 | 🐛 8 | 🌐 V | 📅 2024-02-03 - Web framework written on V inspired by Express and Sinatra.
* [valval](https://github.com/taojy123/valval) ⭐ 156 | 🐛 3 | 🌐 V | 📅 2020-12-15 - Web framework written in V, improved by vweb.
* [pico.v](https://github.com/S-YOU/pico.v) ⭐ 135 | 🐛 4 | 🌐 V | 📅 2020-09-05 - A web server in V based on picoev and picohttpparser.
* [v-jsonrpc](https://github.com/nedpals/v-jsonrpc) ⭐ 36 | 🐛 1 | 🌐 V | 📅 2021-08-21 - Basic JSON-RPC 2.0-compliant server written on V.
* [validate](https://github.com/endeveit/v-validate) ⭐ 24 | 🐛 0 | 🌐 V | 📅 2020-12-30 - A simple library to validate strings in V.
* [vite.v](https://github.com/siguici/vite.v) ⭐ 13 | 🐛 0 | 🌐 V | 📅 2026-07-08 - Seamless [Vite.js](https://vite.dev) integration for Veb applications.
* [west](https://github.com/Dracks/West) ⭐ 9 | 🐛 1 | 🌐 V | 📅 2025-03-08 - A wrapper of vweb to work in a similar way as nestjs works with modules and dependency injection.
* [sessions](https://github.com/einar-hjortdal/sessions) ⭐ 8 | 🐛 0 | 🌐 V | 📅 2026-08-10 - Web-framework-agnostic sessions library.
* [vxbloauth](https://github.com/WolvesFortress/vxbl-oauth) ⭐ 8 | 🐛 0 | 🌐 V | 📅 2021-01-07 - A minimalistic Xbox Live authenticator for vweb.
* [jsonrpcv](https://github.com/Te4nick/jsonrpcv) ⭐ 7 | 🐛 0 | 🌐 V | 📅 2026-04-24 - JSON-RPC 2.0 client+server implementation in pure V.
* [vcurrency](https://github.com/mehtaarn000/vcurrency) ⭐ 7 | 🐛 0 | 🌐 V | 📅 2021-07-05 - API wrapper (written in V) for <https://api.exchangeratesapi.io>.
* [vest](https://github.com/alexferl/vest) ⭐ 7 | 🐛 0 | 🌐 V | 📅 2023-08-01 - A REST client in V.
* [vigest](https://github.com/withs/vigest) ⭐ 4 | 🐛 0 | 🌐 V | 📅 2022-03-29 - Simple client for digest authentication (written in V).
* [v-jwt](https://github.com/deatil/v-jwt) ⭐ 2 | 🐛 0 | 🌐 V | 📅 2026-08-18 - A JWT (JSON Web Token) library for vlang.
* [v-sm3](https://github.com/deatil/v-sm3) ⭐ 1 | 🐛 0 | 🌐 V | 📅 2026-08-18 - A SM3 hash function for vlang.
* [blobly](https://github.com/einar-hjortdal/blobly) ⭐ 0 | 🐛 0 | 🌐 V | 📅 2025-12-17 - Central file server.

## Other

### Articles

* [An introduction to V](https://simonknott.de/articles/VLang.html)
* [How To Make A V Compiler Backend](https://l-m.dev/cs/how_to_make_a_v_backend) - Walkthrough of writing a new codegen backend for V.
* [The V WebAssembly Compiler Backend, Rewritten](https://l-m.dev/cs/the_v_webassembly_compiler_backend_rewrite) - Rewriting V's WebAssembly backend with no external dependencies.

### Books

* [Getting Started with V Programming - Navule Pavan Kumar Rao - Packt 2021 Dec](https://www.amazon.com/Getting-Started-Programming-end-end-ebook/dp/B09FKK3JL7/ref=sr_1_1?keywords=Getting+started+with+V+programming\&qid=1639480830\&sr=8-1) - Introductory book on V.

### Communities

* [V Community](https://github.com/v-community)

### Editor plugins

* [tree-sitter-v](https://github.com/undivisible/tree-sitter-v) ⭐ 3 | 🐛 0 | 🌐 C | 📅 2026-07-27 - Tree-sitter grammar for V language. Maintained fork with modern API, crates.io package, 244 node types.

#### Atom

* [language-v](https://github.com/Cutlery-Drawer/language-v) ⭐ 8 | 🐛 0 | 🌐 Makefile | 📅 2021-03-06 - V language support for Atom (port of vscode-vlang).

#### Emacs

* [v-mode](https://github.com/damon-kwok/v-mode) ⭐ 63 | 🐛 3 | 🌐 Emacs Lisp | 📅 2022-10-07 - Emacs major mode for the V programming language.
* [vlang-mode.el](https://github.com/Naheel-Azawy/vlang-mode.el) ⭐ 14 | 🐛 0 | 🌐 Emacs Lisp | 📅 2023-05-04 - Emacs major mode for the V programming language.

#### Pulsar

* [language-v](https://packages.pulsar-edit.dev/packages/language-v) - V language support for Atom (port of vscode-vlang) (migrated from atom.io)

#### Sublime Text 3

* [vlang-sublime](https://github.com/oversoul/vlang-sublime) ⭐ 19 | 🐛 0 | 📅 2021-08-04 - Sublime Text 3 Support for the Vlang Programming Language.
* [sublime-v](https://github.com/onerbs/sublime-v) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-11-04 - Fully-featured Sublime Text 3 package for the V Programming Language.

#### VS Code

* [vscode-vlang](https://github.com/vlang/vscode-vlang) ⭐ 408 | 🐛 38 | 🌐 TypeScript | 📅 2026-07-26 - V Language extension for Visual Studio Code.
* [v-analyzer](https://github.com/vlang/v-analyzer) ⭐ 206 | 🐛 15 | 🌐 V | 📅 2026-06-20 - Bring IDE features for the V programming language to VS Code.

#### Vim

* [v-vim](https://github.com/ollykel/v-vim) ⭐ 184 | 🐛 6 | 🌐 Vim script | 📅 2024-05-20 - Support for V syntax highlighting in Vim.
* [vim-v](https://github.com/cheap-glitch/vim-v) ⚠️ Archived - Quality syntax highlighting for the V programming language.
* [vim-vtools](https://github.com/zakuro9715/vim-vtools) ⭐ 17 | 🐛 1 | 🌐 Vim script | 📅 2021-06-02 - V tools for Vim, including auto formatting.

#### Zed

* [zed-v](https://github.com/lv37/zed-v) ⭐ 38 | 🐛 5 | 🌐 Rust | 📅 2026-04-22 - Support for V syntax highlighting in Zed.

### Forums

* [r/vlang](https://www.reddit.com/r/vlang)
* [Stack Overflow](https://stackoverflow.com/questions/tagged/vlang)

### GitHub Actions

* [setup-v](https://github.com/vlang/setup-v) ⭐ 33 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-16 - GitHub Action to install and use V in your workflow. Available on the [marketplace](https://github.com/marketplace/actions/setup-vlang).
* [action-create-v-docs](https://github.com/marketplace/actions/create-documentation-for-v-modules) - GitHub action to create documentation for V modules.

### GitHub templates

* [v-project-basement](https://github.com/ArtemkaKun/v-project-basement) ⚠️ Archived - A basement for every V project, that contains universal minimum GitHub CI scripts and issue templates for a V project.

### IDEs with V

* [Vide](https://github.com/IsaiahPatton/Vide) ⭐ 137 | 🐛 5 | 🌐 V | 📅 2025-08-01

### Online IDEs with V

* [V Playground](https://play.vlang.io)
* [V Playground (old)](https://v-wasm.now.sh/)

### Operating Systems & OS Development Examples

* [Simple Linux kernel module example](https://github.com/spytheman/simple_kernel_module_in_v) ⭐ 28 | 🐛 0 | 🌐 Makefile | 📅 2022-08-16 - Demonstration & test of writing a very simple Linux kernel module, using V.
* [limine-v-template](https://github.com/plos-clan/limine-v-template) ⭐ 1 | 🐛 1 | 🌐 Linker Script | 📅 2025-11-07 - A simple template for building a Limine-compliant kernel in V.

### Patterns

* [MVU.v](https://github.com/ArtemkaKun/MVU.v) ⚠️ Archived - MVU pattern (The Elm Architecture) implemented in V programming language.

### Programming contests

* [Advent of Code 2022](https://github.com/vlang/adventofcode) ⭐ 45 | 🐛 0 | 🌐 V | 📅 2026-04-11 - Solution of Advent of Code 2022 in V.
* [SoloLearn Coding Challenges](https://github.com/Serkonda/v-sololearn-coding-challenges) ⚠️ Archived - Implementation of the SoloLearn coding challenges in V.
* [Advent of Code 2019](https://github.com/mvlootman/aoc2019) ⭐ 12 | 🐛 0 | 🌐 V | 📅 2019-12-11 - Solution of Advent of Code 2019 in V.
* [Rosetta Code in V](https://rosettacode.org/wiki/Category:V_\(Vlang\)) - Solutions for Rosetta Code in V.

### Syntax highlighting

* [kate-syntax-highlight-v](https://github.com/Larpon/kate-syntax-highlight-v) ⭐ 20 | 🐛 0 | 📅 2024-07-17 - V syntax highlighting for [Kate](https://kate-editor.org/).
* [scite-v-support](https://github.com/sunnylcw/scite-v-support) ⭐ 2 | 🐛 0 | 📅 2024-06-25 - V syntax highlighting for [SciTE](https://www.scintilla.org/SciTE.html).

### Tutorials

* [V by Example](https://github.com/v-community/v_by_example) ⭐ 178 | 🐛 34 | 🌐 V | 📅 2022-11-28 - V book as [GitBook](https://v-community.gitbook.io/v-by-example/).
* [V learning notes](https://github.com/lydiandy/vlang_note) ⭐ 176 | 🐛 0 | 🌐 V | 📅 2024-09-29 - Personal learning notes in Chinese.
* [Learn V in Y Minutes](https://github.com/v-community/learn_v_in_y_minutes) ⚠️ Archived
* [V for Node Devs](https://github.com/Thigidu/vlang-for-nodejs-developers) ⭐ 29 | 🐛 0 | 📅 2026-01-01 - Vlang for node js developers.

### Videos

* [The V Programming Language](https://www.youtube.com/channel/UCLZIElNyubHOvbfudT7KS1A)
* [V Programming Tutorials](https://www.youtube.com/watch?v=BVCuZ7z7GMY\&list=PLEPMhdsq-gNpFr40A-ZnX-Hu9l-Sp5Oc_)

### Contributors

<a href="https://github.com/ulises-jeremias/awesome-v/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=ulises-jeremias/awesome-v"/>
</a>

Made with [contributors-img](https://contrib.rocks).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
