# Awesome Gemini with stars

A collection of awesome things regarding the [gemini protocol][1] ecosystem.

Please contribute to this list to link to all the awesome gemini projects out there.

Repo mirrors:

* <https://codeberg.org/kr1sp1n/awesome-gemini>
* <https://git.sr.ht/~kr1sp1n/awesome-gemini>
* <https://gitlab.com/kr1sp1n/awesome-gemini>
* <https://github.com/kr1sp1n/awesome-gemini> ⭐ 1,540 | 🐛 9 | 📅 2026-06-07

## What is Gemini

[Excerpt from geminiprotocol.net](https://geminiprotocol.net):

> Gemini is a group of technologies similar to the ones that lie behind your familiar web browser. Using Gemini, you can explore an online collection of written documents which can link to other written documents. The main difference is that Gemini approaches this task with a strong philosophy of "keep it simple" and "less is enough". This allows Gemini to simply sidestep, rather than try and probably fail to solve, many of the problems plaguing the modern web, which just seem to get worse and worse no matter how many browser add-ons or well meaning regulations get thrown at them.

## Gemini Specification

* [Official protocol specification](https://geminiprotocol.net/docs/protocol-specification.gmi)
* [Official gemtext specification](https://geminiprotocol.net/docs/gemtext-specification.gmi)
* [protocol spec discussion and development](https://gitlab.com/gemini-specification/protocol)
* [gemini-text spec discussion and development](https://gitlab.com/gemini-specification/gemini-text)

## Contents

* [Clients](#clients)
  * [Terminal](#terminal)
  * [Graphical](#graphical)
    * [Cross-platform](#cross-platform)
    * [Mobile](#mobile)
    * [Windows](#windows)
    * [MacOS](#macos)
  * [File System](#file-system)
* [Programming](#programming)
* [Related Specifications](#related-specifications)
* [Resources](#resources)
* [Servers](#servers)
* [Services](#services)
* [Tools](#tools)
  * [Gemtext converters](#gemtext-converters)
* [Web proxies](#web-proxies)
* [Bots](#bots)

## Clients

### Terminal

* [gembro](https://git.sr.ht/~rafael/gembro) (Go) - gemini client using [Bubble Tea](https://github.com/charmbracelet/bubbletea) ⭐ 44,605 | 🐛 204 | 🌐 Go | 📅 2026-08-19.
* [Amfora](https://github.com/makeworld-the-better-one/amfora) ⭐ 1,353 | 🐛 9 | 🌐 Go | 📅 2026-07-03 (Go) - "fancy" terminal client. In [maintenance mode](https://www.makeworld.space/2023/08/bye_gemini.html).
* [ncgopher](https://github.com/jansc/ncgopher) ⭐ 222 | 🐛 10 | 🌐 Rust | 📅 2026-06-11 (Rust) - gopher and gemini client for the modern internet.
* [gmi100](https://github.com/ir33k/gmi100) ⭐ 84 | 🐛 1 | 🌐 C | 📅 2024-10-29 (C) - CLI Gemini client written in 100 lines of ANSI C.
* [ereandel](https://github.com/blmayer/ereandel) ⭐ 68 | 🐛 1 | 🌐 Shell | 📅 2026-03-10 (Shell) - terminal client using a custom pager written in POSIX shell script.
* [gplaces](https://github.com/dimkr/gplaces) ⭐ 49 | 🐛 1 | 🌐 C | 📅 2026-06-18 (C) - command-driven, terminal based Gemini client in \~1K LOC of C.
* [min](https://github.com/a-h/min) ⭐ 44 | 🐛 0 | 🌐 Go | 📅 2021-07-21 (Go) - supports advanced features like input and client certificate generation.
* [gemini-fetch](https://github.com/RangerMauve/gemini-fetch) ⭐ 25 | 🐛 2 | 🌐 JavaScript | 📅 2025-05-06 (Node.js) - cURL-like CLI for loading content from Gemini URLs.
* [Gremlin](https://github.com/actuday6418/gremlin) ⭐ 21 | 🐛 0 | 🌐 Rust | 📅 2021-12-03 (Rust) - TUI for browsing Gemini space
* [Romulus](https://github.com/LukeEmmet/Romulus) ⭐ 13 | 🐛 3 | 🌐 C# | 📅 2022-07-21 (C#) - interactive TUI client with menus and mouse support
* [Gemcurses](https://github.com/crusom/Gemcurses) ⭐ 11 | 🐛 1 | 🌐 C | 📅 2024-02-27 (C) - A Gemini client, written in C using ncurses.
* [leo](https://github.com/shantaram3013/leo) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-12-16 (Python) - lightweight, prompt-driven Gemini client.
* [masha](https://codeberg.org/michaelserra/masha) (C) - A simple, fast and reliable terminal Gemini client written in plain C.
* [astronaut](https://sr.ht/~adnano/astronaut/) (Go) - a gemini browser for the terminal
* [Asuka](https://git.sr.ht/~julienxx/asuka) (Rust) - an NCurses-based Gemini client.
* [AV-98](https://tildegit.org/solderpunk/AV-98) (Python) - Gemini client derived from the popular VF-1 Gopher client.
* [AV-98-fork](https://notabug.org/tinyrabbit/AV-98-fork.git) - A fork of AV-98.
* [bollux](https://tildegit.org/acdw/bollux) (Bash) - bash Gemini client.
* [bombadillo](https://bombadillo.colorfield.space/) (Go) - combined Gopher, Gemini, Finger, and File client with vim-inspired key mappings.
* [cgmnlm](https://git.sr.ht/~rwa/cgmnlm) (C) - colorful gemini line-mode client, fork of gmni.
* [diohsc](https://mbays.sdf.org/diohsc/) (Haskell) - simple line-based command-response terminal user interface with ANSI colour.
* [Elpher](https://thelambdalab.xyz/elpher/) (Emacs) - combined Gopher and Gemini client for the popular text editor / operating system.
* [gelim](https://sr.ht/~hedy/gelim/) (Go) - A minimalist line-mode smolnet client written in go.
* [gem.awk](http://git.vgx.fr/gem.awk/file/gem.awk.html) (Awk) - minimal but usable interactive Gemini client in < 250 LOC of Awk.
* [gemini-demo-1](https://tildegit.org/solderpunk/gemini-demo-1) (Python) - minimal but usable interactive Gemini client in < 100 LOC of Python 3.
* [gemini-demo-2](https://tildegit.org/solderpunk/gemini-demo-2) (Lua) - minimal but usable interactive Gemini client in < 100 LOC of Lua.
* [gemini-demo-3](https://tildegit.org/solderpunk/gemini-demo-3) (Go) - minimal but usable interactive Gemini client in not quite < 100 LOC of Go.
* [gemivim](https://sr.ht/~k1nkreet/gemivim/) (Vim) - simple VIM plugin for browsing Gemini pages
* [gmi](https://sr.ht/~chambln/gmi) (Shell) - Tiny Gemini browser written in POSIX-compliant shell. Highly hackable, portable shell script under 200 lines.
* [gmni](https://sr.ht/~sircmpwn/gmni/) (C) - CLI utility (like curl) and line-mode browser.
* [Lagrange](https://git.skyjake.fi/skyjake/lagrange) (C) - TUI client for Gemini, Gopher, Nex, and Spartan with multiple tabs, bookmarks and more.
* [Offpunk](https://sr.ht/~lioploum/offpunk/) (Python) - Gemini, gopher, spartan and http/html offline-first browser.
* [Omura](https://github.com/fzn0x/omura) (Node.js, Bun) - Pushing lightweight gemtext-based internet CLI client.
* [Scroll-Term](https://gitlab.com/clseibold/scroll-term) (Go) - Gemini, Nex, and Scroll terminal client with audio streaming support.
* [Telescope](//telescope.omarpolo.com) (C) - w3m-inspired, multi-protocol client that supports Gemini, Gopher and Finger
* [tinmop](https://www.autistici.org/interzona/tinmop.html) (Common Lisp) - opinionated Mastodon and Gemini client
* [tgmi](https://framagit.org/apm04/tgmi) (python) - full-featured CLI terminal-based Gemini client

### Graphical

#### Cross-platform

* [Agregore](https://github.com/RangerMauve/agregore-browser#fetch-api-for-gemini) ⭐ 921 | 🐛 103 | 🌐 JavaScript | 📅 2026-07-13 - (Electron.js) - peer to peer web browser with support for loading Gemini pages.
* [Kristall](https://github.com/MasterQ32/kristall) ⭐ 796 | 🐛 43 | 🌐 C++ | 📅 2026-04-26 (C++) - graphical Gopher and Gemini client using QT.
* [Geopard](https://github.com/ranfdev/Geopard) ⭐ 206 | 🐛 41 | 🌐 Rust | 📅 2025-09-01 (Rust) - A colorful, adaptive gemini browser.
* [Alhena](https://github.com/mochaman/alhena) ⭐ 59 | 🐛 1 | 🌐 Java | 📅 2026-08-26 - (Java) themes, color emojis on Mac, inline images, etc. jlinked exes do not require Java.
* [Molasses](https://github.com/jjsimpso/molasses) ⭐ 36 | 🐛 2 | 🌐 Racket | 📅 2026-07-05 (Racket) - full-featured graphical Gopher and Gemini client with tabs.
* [Fossil](https://github.com/koyuspace/fossil) ⚠️ Archived (Vala) - GTK3 Gemini browser written in Vala for desktop and mobile.
* [Yoda](https://github.com/YGGverse/Yoda) ⭐ 23 | 🐛 8 | 🌐 Rust | 📅 2026-05-12 (Rust) - GTK 4 / Libadwaita client written in Rust.
* [eGemi](https://github.com/nfnitloop/egemi) ⭐ 6 | 🐛 4 | 🌐 Rust | 📅 2025-08-17 (Rust) - Read gemtext and other plaintexts via `gemini://` *and* `https://`. (uses [egui](https://github.com/emilk/egui) ⭐ 30,195 | 🐛 1,131 | 🌐 Rust | 📅 2026-08-27)
* [spacewar](https://github.com/ResonAtom/spacewar) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2020-08-24 (Electron.js) - EXPERIMENTAL and UNSTABLE Gemini browser running on Electron.
* [Alrisha](https://git.sr.ht/~fabrixxm/alrisha) (QML) - QML-based Gemini client.
* [Castor](https://git.sr.ht/~julienxx/castor) (Rust) - graphical Gemini client using GTK.
* [Eva](https://codeberg.org/jeang3nie/eva) (Rust) - a Gemini protocol browser in Gtk4
* [Fafi](https://git.sr.ht/~soapdog/fafi-browser) (Racket) - graphical Gemini browser written in Racket.
* [Galacteek](https://gitlab.com/galacteek/galacteek) (Python) - Browser for the distributed web, with support for Gemini and IPFS.
* [Gemalaya](https://gitlab.com/cipres/gemgemgem) (Python/QML) - Keyboard-driven Gemini browser with builtin web-to-gemini proxy
* [Gerbil](https://gitlab.com/armen138/gerbil) (Python) - Gemini and Spartan browser written in python with GTK and LibHandy for desktop and mobile
* [Gem2Browser](https://swee.codes/gem2browser) (Python/Flask) - A "web client" for Gemini that's made to support most browsers.
* [Lagrange](https://git.skyjake.fi/skyjake/lagrange) (C) - desktop GUI client for Gemini, Gopher, Nex, and Spartan with inline image viewing, multiple tabs, bookmarks and more.
* [Moonlander](https://sr.ht/~admicos/moonlander/) (Rust) - the fanciest Gemini client in the entire solar system.
* [Profectus](https://gitlab.com/clseibold/profectus) (Go) - Gemini, Nex, Spartan, and Scroll client with tabs, music player, streaming, and expansive theming.
* [vimini](https://git.sr.ht/~lufte/vimini) (Rust) - Desktop gemini browser inspired by qutebrowser and Vim.

#### Mobile

* [Deedum](https://github.com/snoe/deedum) ⭐ 142 | 🐛 15 | 🌐 Dart | 📅 2025-07-31 (Dart) - an Android and iOS client made with Flutter.
* [Buran](https://github.com/Corewala/Buran) ⭐ 134 | 🐛 25 | 🌐 Kotlin | 📅 2023-07-07 (Kotlin/Java) - Gemini browser for Android, fork of Ariane.
* [Elaho](https://github.com/pitr/gemini-ios) ⭐ 129 | 🐛 21 | 🌐 Swift | 📅 2023-11-26 (Swift) - full featured Gemini protocol browser for iOS.
* [Gem](https://open-store.io/app/gem.aaron) (Python) - Gemini client for Ubuntu Touch.
* [Lagrange](https://git.skyjake.fi/skyjake/lagrange) (C) - mobile GUI client for Android, iOS, and iPadOS implementing Gemini, Gopher, Nex, and Spartan protocols with inline image viewing, multiple tabs, bookmarks and more.
* [Narrow32](https://apps.apple.com/us/app/narrow32/id6755984760) ([Android](https://play.google.com/store/apps/details?id=com.alxsla.narrow32\&hl=en-US)) (Swift/Kotlin) - Browser optimized for slow connections with Gemini and Gopher protocol support for iOS and Android.
* [Phaedra](https://oppen.digital/software/phaedra/) (Java) - Gemini client for Android supporting even very old ones; author recommends using Ariana if a current Android is at hand.
* [Rosy Crow](https://rosy-crow.app) (C#) - An Android client built using .NET MAUI.
* [Xenia](https://codeberg.org/tslocum/xenia) (Java) - Gemini proxy for Android.

#### Windows

* [GemiNaut](https://www.marmaladefoo.com/pages/geminaut) (C#) - user friendly graphical Gemini client for MS Windows.

#### MacOS

* [Jimmy](https://github.com/jfoucher/Jimmy) ⭐ 81 | 🐛 8 | 🌐 Swift | 📅 2023-09-10 (SwiftUI) - a lightweight native Gemini client for MacOS

#### AmigaOS

* [AmiGemini](http://aminet.net/package/comm/net/AmiGemini)

#### File System

* [GeminiFS](https://github.com/harkaitz/c-geminifs) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2024-11-26 (C) - FUSE filesystem for Gemini capsules.

## Programming

* [go-gemini](https://github.com/makew0rld/go-gemini) ⭐ 71 | 🐛 0 | 🌐 Go | 📅 2026-04-21 (Go) - more recent fork of the library above.
* [gig](https://github.com/pitr/gig) ⭐ 65 | 🐛 4 | 🌐 Go | 📅 2022-07-09 (Go) - Gemini framework.
* [derhuerst/gemini](https://github.com/derhuerst/gemini) ⭐ 52 | 🐛 4 | 🌐 JavaScript | 📅 2025-03-19 (Node.js) - server & client lib.
* [a-h/gemini](https://github.com/a-h/gemini) ⭐ 52 | 🐛 2 | 🌐 Go | 📅 2025-04-21 (Go) - Applications and libraries for building applications on Gemini.
* [html2gemini](https://github.com/LukeEmmet/html2gemini) ⭐ 24 | 🐛 2 | 🌐 Go | 📅 2022-07-23 (Go) - package library to convert HTML to Gemini (see also html2gmi for command line application)
* [gemclient](https://github.com/Koshroy/gemclient) ⭐ 15 | 🐛 0 | 🌐 Nim | 📅 2021-10-30 (Nim) - rich client library for the Gemini Protocol.
* [SmolNetSharp](https://github.com/LukeEmmet/SmolNetSharp) ⭐ 14 | 🐛 0 | 🌐 C# | 📅 2022-07-23 (C#) - cross platform .NET (core/framework) client library for building Gemini and Gopher clients
* [kaksik](https://github.com/sergetymo/kaksik) ⭐ 12 | 🐛 3 | 🌐 TypeScript | 📅 2024-05-19 (Deno/TypeScript) - middleware library for building server applications.
* [dremini](https://github.com/marty1885/dremini) ⭐ 11 | 🐛 0 | 🌐 C++ | 📅 2026-08-25 (C++) - Highly concurrent C++ Gemini server and client library
* [gemini](https://github.com/kulak/gemini) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-10-17 (Go) - Server side Gemini protocol + Titan protocol implementation that matches standard GO http API.
* [gmir](https://github.com/codesoap/gmir) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2024-11-09 (Go) - A reader for gmi files
* [warmuuh/jemini](https://github.com/warmuuh/jemini/tree/main/gemini-client) ⭐ 9 | 🐛 0 | 🌐 Java | 📅 2021-04-23(Java) - reactive gemini-client, part of jemini-project
* [Opal](https://github.com/aschuhardt/Opal) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2024-01-06 (C#) - Gemini client library targeting .NET Standard 2.0.  Built-in support for TOFU and client certificates.
* [gemax](https://github.com/ninedraft/gemax) ⭐ 8 | 🐛 3 | 🌐 Go | 📅 2026-04-09 (Go) - a golang gemini stack, inspired by go STD http library.
* [geminic](https://github.com/WarpEngineer/geminic) ⭐ 7 | 🐛 0 | 🌐 Erlang | 📅 2021-07-01 (Erlang) - An Erlang library for building Gemini protocol clients.
* [cuipod](https://github.com/aegis-dev/cuipod) ⭐ 5 | 🐛 0 | 🌐 C# | 📅 2021-12-15 (C#) - Simple yet flexible framework for Gemini protocol server.
* [phos](https://github.com/omar-polo/phos) ⭐ 5 | 🐛 1 | 🌐 Common Lisp | 📅 2025-10-07 (Common Lisp) - Gemini client library and experimental GUI
* [ggemini](https://github.com/YGGverse/ggemini) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2026-05-12 (Rust) - Glib/Gio-oriented client for Gemini protocol
* [gemini-php](https://github.com/YGGverse/gemini-php) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2024-08-02 (PHP) - Composer library that includes TLS / socket client, Gemtext parser and DokuWiki tools.
* [ggemtext](https://github.com/YGGverse/ggemtext) ⭐ 0 | 🐛 1 | 🌐 Rust | 📅 2026-05-12 (Rust) - Glib-oriented Gemtext API
* [titanite](https://github.com/YGGverse/titanite) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2025-02-24 (Rust) - Client/Server library for Gemini protocol with Titan support
* [gemtext-php](https://github.com/YGGverse/gemtext-php) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2024-07-08 (PHP) - object-oriented library for Gemtext operations
* [Agunua](https://framagit.org/bortzmeyer/agunua) (Python) - Gemini library to write clients. Includes IRI support, gemtext parsing and CLI tool.
* [go-gemini](https://git.sr.ht/~yotam/go-gemini) (Go) - library that provides an easy interface to create client and servers.
* [gusmobile](https://git.sr.ht/~rwa/gusmobile) (Python) - gemini client for Pyhton (used by geminispace.info)
* [ignition](https://github.com/cbrews/ignition) (Python) - Gemini client transport/request library for python3.
* [qgeminiserver](https://github.com/doga/qgeminiserver) (Deno/TypeScript) - framework for server applications. A [kaksik](https://github.com/sergetymo/kaksik) ⭐ 12 | 🐛 3 | 🌐 TypeScript | 📅 2024-05-19 fork that fixes bugs and keeps away bit-rot.
* [ruby-net-text](https://git.umaneti.net/ruby-net-text/) (Ruby) - Gemini support in Net::\* and URI::\* stack.

## Related Specifications

* [GemPub Specification](https://codeberg.org/oppenlab/gempub) - Gempub, the Gemini e-book (and capsule archive) container specification.
* [Gemini TinyLog Specification](https://codeberg.org/bacardi55/gemini-tinylog-rfc) - A Tinylog is a simple file with all "microblog" style entries to share small contents and interact with other geminauts' tinylog.
* [Adding Emoji Favicons to Gemini](https://portal.mozz.us/gemini/mozz.us/files/rfc_gemini_favicon.gmi) - Optional extension by Michael Lazar to the Gemini Protocol, with the goal to set a Unicode emoji as favicon for a site.

## Resources

* [Gemini Specification](https://geminiprotocol.net/docs/) - the Gemini protocol documentation.
* [geminiprotocol.net/software/](https://portal.mozz.us/gemini/geminiprotocol.net/software/) - list of Gemini software.

## Servers

* [Agate](https://github.com/mbrubeck/agate) ⭐ 747 | 🐛 7 | 🌐 Rust | 📅 2026-08-26 (Rust) - simple Gemini server for static files.
* [Jetforce](https://github.com/michael-lazar/jetforce) ⭐ 218 | 🐛 7 | 🌐 Python | 📅 2026-08-25 (Python) - built-in static file server with support for gemini directories and CGI scripts.
* [gmid](https://github.com/omar-polo/gmid) ⭐ 120 | 🐛 14 | 🌐 C | 📅 2026-08-01 (C) - simple and secure Gemini server.
* [a-h/gemini](https://github.com/a-h/gemini) ⭐ 52 | 🐛 2 | 🌐 Go | 📅 2025-04-21 (Go) - Server for Linux, Mac, Raspberry Pi. Supports SNI for multiple domains on the same server, has Docker image.
* [GLV-1.12556](https://github.com/spc476/GLV-1.12556) ⭐ 45 | 🐛 0 | 🌐 Lua | 📅 2026-01-04 (Lua) - the first Gemini protocol server with a lot of features.
* [Germinal](https://github.com/jfmcbrayer/germinal) ⭐ 44 | 🐛 0 | 🌐 Common Lisp | 📅 2021-05-11 (Common Lisp) - serves any type of document with an appropriate mime type.
* [geminid](https://github.com/jovoro/geminid/) ⭐ 40 | 🐛 1 | 🌐 C | 📅 2024-06-05 (C) - Gemini Server in C.
* [geminim](https://github.com/ardek66/geminim) ⭐ 40 | 🐛 2 | 🌐 Nim | 📅 2022-07-09 (Nim) - an async lightweight Gemini server made in Nim.
* [Mehari](https://github.com/Psi-Prod/Mehari) ⭐ 40 | 🐛 0 | 🌐 OCaml | 📅 2026-08-14 - Featureful server in OCaml
* [blizanci](https://github.com/mk270/blizanci) ⭐ 33 | 🐛 8 | 🌐 Erlang | 📅 2026-05-01 (Erlang) - server designed primarily for robustness and security.
* [net-gemini](https://github.com/jackdoe/net-gemini) ⭐ 33 | 🐛 0 | 🌐 Go | 📅 2021-08-25 (Go) - gemini server inspired by Molly Brown.
* [Gemeaux](https://github.com/brunobord/gemeaux) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2025-04-06 (Python) - server using only the Python standard library.
* [twinstar](https://github.com/panicbit/twinstar) ⭐ 18 | 🐛 7 | 🌐 Rust | 📅 2025-09-09 (Rust) - gemini server implementation.
* [gmifs](https://github.com/n0x1m/gmifs) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2021-07-29 (Go) - Gemini file server with auto indexing support, caching and auto TLS key pair creation.
* [Bunkum](https://github.com/PlanetBunkum/Bunkum) ⭐ 15 | 🐛 14 | 🌐 C# | 📅 2025-06-25 (C#) - Open source .NET Gemini/Titan/Gopher/HTTP(S) request server.
* [Windmark](https://github.com/gemrest/windmark) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-06-13 (Rust) - An elegant and highly performant async Gemini server framework
* [atlas](https://github.com/Alumniminium/atlas) ⭐ 13 | 🐛 1 | 🌐 C# | 📅 2025-10-24 (C#) - .NET7 Gemini/Titan/Spartan server w/ vhost and cgi support.
* [Hydepark](https://github.com/spektom/hydepark) ⭐ 13 | 🐛 0 | 🌐 Rust | 📅 2021-03-13 (Rust) - discussion forum application for Gemini.
* [Denoscuri](https://github.com/caranatar/denoscuri) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2020-07-18 (Typescript) - simple Gemini server written using Deno and Typescript.
* [Marami](https://github.com/MagnificentPako/Marami/) ⭐ 11 | 🐛 0 | 🌐 Prolog | 📅 2020-09-07 (Prolog) - server written in Prolog.
* [Gneto](https://github.com/pgorman/gneto) ⭐ 10 | 🐛 3 | 🌐 Go | 📅 2021-07-05 (Go) - Gemini over HTTP proxy, with support for client certificates and CSS customization.
* [jemini](https://github.com/warmuuh/jemini) ⭐ 9 | 🐛 0 | 🌐 Java | 📅 2021-04-23(Java) - dual gemini/http server on top of jetty with spring-boot integration
* [Gemini Dock](https://github.com/mathiscode/gemini-dock) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-06 (TypeScript) - an extensible Gemini server with a built-in database and easy dynamic site creation focused on DX
* [JAGS-php](https://github.com/codeandcreate/JAGS-PHP) ⭐ 7 | 🐛 0 | 🌐 PHP | 📅 2022-02-04 (PHP) - fork of gemini-php with support of dynamic pages.
* [Titan](https://github.com/jahzielv/titan) ⭐ 7 | 🐛 1 | 🌐 Rust | 📅 2020-10-10 (Rust) - simple TOML-configured Gemini server and an Express-like Gemini server framework.
* [aiogemini](https://github.com/rcarmo/aiogemini) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-01-04 (Python) - minimalist Python 3 `asyncio` server.
* [Apogee](https://github.com/bunburya/apogee) ⭐ 6 | 🐛 0 | 🌐 Kotlin | 📅 2023-12-26 (Kotlin) - Gemini server written in Kotlin for the JVM.
* [Loxy](https://github.com/aschuhardt/Loxy) ⭐ 6 | 🐛 1 | 🌐 C# | 📅 2023-10-10 (C#) - Gemini to HTTP proxy, exposes any capsule to the web as stylable HTML (based on the Opal library).
* [Doppio](https://github.com/bhavanki/doppio) ⭐ 5 | 🐛 1 | 🌐 Java | 📅 2025-05-25 (Java) - single-JAR Gemini server with CGI, authentication, and Atom feed support.
* [jsonresume-gemini](https://github.com/michaelcaplan/jsonresume-gemini) ⭐ 4 | 🐛 0 | 🌐 PHP | 📅 2022-03-27 (PHP) -  single purpose server implementation of the Gemini protocol to serve up your JSON Resume.
* [tripod](https://github.com/aartaka/tripod) ⭐ 4 | 🐛 4 | 🌐 Common Lisp | 📅 2022-09-21 (Common Lisp) - Polyglot blog engine serving Gemtext, Gopher, HTML, and plaintext
* [Yo!](https://github.com/YGGverse/Yo/tree/gemini) ⭐ 4 | 🐛 7 | 🌐 PHP | 📅 2024-04-18 (PHP) - Search server and crawler with history snap support, based on [Manticore](https://github.com/manticoresoftware)
* [gem](https://github.com/wrclark/gem) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2025-05-17 (C) - static file server with many features
* [kepler](https://github.com/ambyshframber/kepler) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2022-08-07 - simple gemini server in rust
* [Earl Server](https://github.com/mrletourneau/EarlServer) ⭐ 2 | 🐛 5 | 🌐 Kotlin | 📅 2020-12-03 (Kotlin) - Gemini fileserver for the JVM.
* [Maple](https://github.com/gemrest/maple) ⭐ 2 | 🐛 0 | 🌐 C++ | 📅 2026-03-04 (C++) - A very simple static Gemini server, now with Titan support!
* [mollyb](https://github.com/augmentedlogic/mollyb) ⭐ 2 | 🐛 0 | 🌐 Java | 📅 2026-06-18 (Java) - A basic Gemini server in Java
* [KevaChat](https://github.com/kevachat/geminiapp) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2024-03-07 (PHP) - client/server Chat in Blockchain
* [Pulsar](https://github.com/YGGverse/Pulsar) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2024-05-07 (PHP) - RSS aggregation server for Gemini Protocol
* [β-Doku](https://github.com/YGGverse/bdoku) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2024-03-07 (PHP) - DokuWiki Satellite for Gemini Protocol
* [titanit](https://github.com/YGGverse/titanit) ⭐ 1 | 🐛 0 | 🌐 Rust | 📅 2025-02-24 (Rust) - File share server for Titan protocol with Gemini frontend
* [StaticGeminiServer](https://github.com/marek22k/StaticGeminiServer) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2022-08-31 ([Codeberg](https://codeberg.org/mark22k/StaticGeminiServer)) (Ruby) - a simple more or less stable gemini server for static files
* [gemini-server-clj](https://github.com/aburd/gemini-server-clj) ⭐ 0 | 🐛 3 | 🌐 Clojure | 📅 2024-02-12 (Clojure) - simple gemini server for serving static files
* [βtracker](https://github.com/YGGverse/btracker-gemini) ⚠️ Archived (Rust) - BitTorrent catalog for the Gemini protocol
* [Dʒɛmɪni](https://sr.ht/~rwv/dezhemini/) (Racket) - server with features like SNI and CGI.
* [Diamant](https://git.umaneti.net/diamant/) (Ruby) - simple Gemini server for static files.
* [Duckling proxy 🦆](https://portal.mozz.us/gemini/gemini.marmaladefoo.com/blog/31-Aug-2020_The_Duckling_Proxy.gmi) (Go) - scheme-specific filtering proxy for Gemini clients to access the web.
* [Enceladus](https://github.com/modotte/Enceladus) (F#) - A simple Gemini protocol server implementation in .NET Core and F#.
* [Ergol](http://adele.work/code/ergol/ergol.gmi) (PHP) - light Gemini server able to host several capsules with different cerificates.
* [GeGoBi](https://tildegit.org/solderpunk/gegobi) (Python) - server to facilitate easy Gemini-Gopher bi-hosting.
* [Gemi](https://jsr.io/@nfnitloop/gemi) (TypeScript/Deno) - Natively serves Gemtext over HTTP. (Or as HTML for gemtext-unaware browsers)
* [gemini-ipfs-gateway](https://git.sr.ht/~hsanjuan/gemini-ipfs-gateway) (Go) - an IPFS Gateway that makes IPFS content available over the Gemini protocol.
* [gemini-server](https://hackage.haskell.org/package/gemini-server) (Haskell) - lightweight server for the Gemini protocol.
* [geminid](https://www.upyum.com/cgit.cgi/geminid) (Scheme) - Gemini Server in CHICKEN Scheme.
* [gemini-php](https://opensource.glasgow.social/gemini-php) (PHP) - simple Gemini server in PHP.
* [geminispace-jsdoc-server](https://github.com/doga/geminispace-jsdoc-server) A Gemini server for serving JSDoc documentation on the Deno runtime.
* [gmnd](https://code.smolnet.org/micke/gmnd) (Python) - packaged Gemini server with support for CGI and indexing
* [gmnisrv](https://sr.ht/~sircmpwn/gmnisrv/) (C) - high-performance Gemini server for POSIX systems.
* [Gemserv](https://portal.mozz.us/gemini/80h.dev/projects/gemserv/) (Rust) - server with features like vhosts, CGI, SCGI, reverse-proxying and more.
* [laika](https://sr.ht/~gbmor/laika/) (Rust) - async Gemini protocol server.
* [levior](https://gitlab.com/cipres/levior) (Python) - HTTP to Gemini gateway, allowing you to browse regular websites with any Gemini client
* [Lupa Pona](https://github.com/kensanata/lupa-pona) (Perl) - simple single directory Gemini server.
* [Molly Brown](https://tildegit.org/solderpunk/molly-brown) (Go) - full-featured Gemini server implemented in Go.
* [MoonGem](https://sr.ht/~panda-roux/MoonGem) (C) - gemini server with inline Lua scripting for dynamic content generation.
* [Orbit](https://tildegit.org/sumpygump/orbit) (PHP) - Gemini server implemented in PHP.
* [Phoebe](https://alexschroeder.ch/cgit/phoebe/about/) (Perl) - Gemini/web wiki.
* [pollux](https://git.sr.ht/~julienxx/pollux) (Rust) - simple server that will only serve one `index.gemini` file.
* [rc-gemd](https://sr.ht/~moody/rc-gemd) (Shell) - simple Gemini server written in rc (for plan9 operating systems).
* [Satellite](https://sr.ht/~gsthnz/satellite/) (Go) - small Gemini server for serving static files.
* [Shavit](https://git.sr.ht/~yotam/shavit) (Go) - configurable Gemini server for UNIX operating systems.
* [Smolver](https://gitlab.com/g2764/smolver) (Swift) - a small Gemini server.
* [Space-Age](https://gitlab.com/lambdatronic/space-age) (Clojure) - Gemini server written in Clojure.
* [Taurus](https://git.sr.ht/~garritfra/taurus)(Rust) - A Concurrent Gemini Server.
* [twins](https://codeberg.org/tslocum/twins) (Go) - YAML-configured Gemini server supporting vhosts, FastCGI and reverse-proxying.
* [vger](https://tildegit.org/solene/vger) (C) - Gemini server written in C used with inetd.
* [SpaceBeans](https://git.usebox.net/spacebeans/about/) (Scala) - supports virtual hosting, user directories, classic CGI.
* [vostok](https://got.any-key.press/?action=summary\&path=vostok.git) (**gemini://vostok.any-key.press/**) (C++11) - gemini server

## Services

* **gemini://tlgs.one** - ([http version](https://tlgs.one)) Another public search provider for Gemini([repo](https://github.com/marty1885/tlgs) ⭐ 38 | 🐛 2 | 🌐 C++ | 📅 2026-07-27).
* **gemini://kevachat.duckdns.org** - KevaChat clearnet node for Gemini ([repo](https://github.com/kevachat/geminiapp) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2024-03-07).
* **gemini://betahowto.duckdns.org** - Yggdrasil DokuWiki Satellite ([repo](https://github.com/YGGverse/bdoku) ⭐ 1 | 🐛 0 | 🌐 PHP | 📅 2024-03-07)
* **gemini://flounder.online** ([https version](https://flounder.online/)) - host small Gemini web pages over https and Gemini ([repo](https://github.com/alexwennerberg/flounder) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2026-08-27).
* **gemini://kvazar.duckdns.org** - Observe Kevacoin Universe ([repo](https://github.com/kvazar-network/geminiapp) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2024-03-07)
* **gemini://warmedal.se/\~antenna/** - Geminispace aggregator
* **gemini://geminispace.info** - public search provider for Gemini ([repo](https://sr.ht/~rwa/geminispace.info)).
* **gemini://geddit.glv.one** - interactive link service (with comments).
* **gemini://glv.one** - free platform as a service (PaaS) that runs any Gemini server (packaged as a Docker image) in the cloud.
* **gemini://gemini.omarpolo.com/cgi/gempkg/** - interface for the OpenBSD ports collection.
* **gemini://gemplex.space/** - experimental Search Engine for Gemini written in Go
* **gemini://kennedy.gemi.dev/** - public search provider for Gemini
* **gemini://aurasearch.ddns.net/** - Search Engine for Gemini, Nex, Spartan, and Scroll
* **gemini://tictactoe.lanterne.chilliet.eu** - Tic Tac Toe game ([repo](https://framagit.org/MCMic/gemini-tictactoe)).
* **gemini://tilde.cafe/\~spellbinding/game/cgi?** - make words with specified letters
* **gemini://tilde.cafe/\~spellbinding/wordo/cgi?** - a wordle-like game
* **gemini://tilde.cafe/\~spellbinding/wall/cgi** - A public wall where you can leave a message
* **gemini://ur.gs/** - translate from en->es and es->en ([repo](https://code.ur.gs/lupine/capsule/src/branch/main/src/cgi-bin/translate)).
* **gemini://rawtext.club/\~sloum/geminews/** - Daily news feeds proxied to gemini.
* **gemini://rawtext.club/\~sloum/cgi/othello/** - Play othello/reversi against a computer opponent over gemini.
* **gemini://rawtext.club/\~sloum/cgi/weather** - US weather reports by zip code.
* **gemini://tilde.cafe/\~stack/weather** - weather forecast powered by wttr.in
* [gemlog.blue](https://gemlog.blue) - Gemini hosting from a web frontend.
* **gemini://houston.gmi.bacardi55.io** - A simple tool to check if a capsule is up or not
* **gemini://fumble-around.mediocregopher.com** - Explore gemspace by hopping from one random interesting page to the next.
* **gemini://hashnix.club:1958/** - hashnix.club email service provider for Gemini

## Tools

* [gemget](https://github.com/makew0rld/gemget) ⭐ 81 | 🐛 4 | 🌐 Go | 📅 2025-05-28 (Go) - Command line downloader for the Gemini protocol.
* [gloggery](https://github.com/kconner/gloggery) ⭐ 33 | 🐛 1 | 🌐 Go | 📅 2026-02-21 (Go) - basic static site generator for blogs in Gemini.
* [Hugo-2-Gopher-and-Gemini](https://github.com/mkamarin/Hugo-2-Gopher-and-Gemini) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-04-07 (Python) - A Hugo theme to convert a Hugo site to Gemini or Gopher.
* [Gemini Diagnostics](https://github.com/michael-lazar/gemini-diagnostics) ⭐ 27 | 🐛 3 | 🌐 Python | 📅 2022-07-22 - A torture test for gemini servers
* [astroget](https://github.com/zzo38/scorpion/blob/trunk/astroget.c) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2026-06-24 (C) - Command line tool to download and upload files from Gemini, Gopher, Scorpion, and Spartan servers.
* [gempost](https://github.com/justlark/gempost) ⭐ 18 | 🐛 2 | 🌐 Rust | 📅 2024-05-04 (Rust) - Simple static site generator for Gemini blogs.
* [gemmit](https://github.com/t-900-a/gemmit) ⭐ 8 | 🐛 0 | 🌐 Go | 📅 2021-04-20 (Go) - social news aggregation and web content rating website for the gemini protocol.
* [Gopher-and-Gemini-Walker](https://github.com/mkamarin/Gopher-and-Gemini-Walker) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-01-29 (Python) - Terminal client (without network connectivity) to navigate a folder structure containing a Gemini capsule or Gopher hole.
* [pulsarss](https://github.com/YGGverse/pulsarss) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2025-09-03 (Rust) - Crawl & Convert RSS feeds into static Gemtext
* [Pulsar](https://github.com/YGGverse/Pulsar) ⭐ 2 | 🐛 0 | 🌐 PHP | 📅 2024-05-07 (PHP) - RSS Aggregator for Gemini Protocol
* [gemini-dl](https://github.com/YGGverse/gemini-dl) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2025-11-11 (PHP) - CLI batch downloader for Gemini protocol
* [CAPCOM](https://tildegit.org/solderpunk/CAPCOM) (Python) - Atom feed aggregator for gemini.
* [certified](https://code.lag.net/robey/certified) (Python) - Generate TOFU TLS certificates for gemini servers.
* [cl-yag](git://bitreich.org/cl-yag) (Common-Lisp) - Static site generator producing gemini, gopher and html.
* [comitium](https://git.nytpu.com/comitium) (C) - A feed aggregator for gemini supporting many formats and protocols.
* [gemfreely](https://git.agnos.is/projectmoon/gemfreely) (Rust) - Synchronize gemlogs to the Fediverse via WriteFreely.
* [gemini-antenna](https://notabug.org/tinyrabbit/gemini-antenna) (Python) - A feed-aggregator for Gemini, triggered by submissions.
* [geminize](https://addons.mozilla.org/en-US/firefox/addon/geminize/) - Firefox addon that redirects gemini:// URLs and links to a customizable HTTP-to-Gemini proxy.
* [gemlog.sh](https://git.sr.ht/~nytpu/gemlog.sh) (Bash) - Utility for writing and managing gemini logs (gemlogs) and atom feeds (simple gemini static site generator/framework).
* [gem.git](https://git.sr.ht/~fkfd/git.gmi/) (Python) - git frontend CGI script.
* [GemPress](https://git.sr.ht/~aprates/gempress) (C) - Yet another Gemini publishing framework with HTML and Atom support, written in Bash and Sugar-C.
* [gemtexter](https://codeberg.org/snonux/gemtexter) (Bash) - Site generator and blog engine for Gemini. Generates Atom and Gemfeeds , and also does Gemtext to HTML and Markdown conversion.
* [gmitohtml](https://gitlab.com/tslocum/gmitohtml) (Go) - proxy that renders Gemini pages using HTML.
* [gmnigit](https://git.sr.ht/~kornellapacz/gmnigit) (Go) - static git gemini viewer.
* [gssg](https://git.sr.ht/~gsthnz/gssg) (Go) - simple gemini static site generator. Generates pages, index and atom feeds.
* [kiln](https://git.sr.ht/~adnano/kiln) (Go) - simple static site generator for Gemini sites.
* [Lupa](https://framagit.org/bortzmeyer/lupa) - crawler to explore the geminispace and make statistics (you can see them at \_\_gemini://gemini.bortzmeyer.org/software/lupa/stats.gmi ).
* [Manisha](https://framagit.org/bortzmeyer/manisha) - Nagios (and compatible, such as Icinga) plugin to monitor Gemini servers.
* [spacewalk](https://tildegit.org/sloum/spacewalk) (Go) - Page-hash based feed aggregator for gemini.
* [MastoGem](https://git.rdelaage.ovh/rdelaage/mastoGem) (Go) - Mastodon proxy for Gemini.
* [spsg](https://git.sr.ht/~sbr/spsg) (Go) - Small Protocol Static Generator - Produces Gemini/Gopher/Nex indexes based on gemini posts.

### Gemtext converters

* [md2gemini](https://github.com/makeworld-the-better-one/md2gemini) ⚠️ Archived (Python) - converter from Markdown to the Gemini text format.
* [dioscuri](https://github.com/wooorm/dioscuri) ⭐ 43 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-09 (JS) - A Gemtext parser with interfaces to transform to and from mdast (markdown ast) and to compile to HTML.
* [html2gmi](https://github.com/LukeEmmet/html2gmi) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2022-04-16 (Go) - command line utility to convert HTML to gemtext
* [Hugo-2-Gopher-and-Gemini](https://github.com/mkamarin/Hugo-2-Gopher-and-Gemini) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2026-04-07 (Python) - A Hugo theme to convert a Hugo site to Gemini or Gopher.
* [gemini-to-html](https://github.com/RangerMauve/gemini-to-html) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2024-03-13 (Node.js) - JavaScript library for parsing Gemini pages, and for rendering them to HTML.
* [gmi2html](https://github.com/shtanton/gmi2html) ⭐ 28 | 🐛 2 | 🌐 Zig | 📅 2023-09-16 (Zig) - tiny gemtext to HTML converter with a focus on performance.
* [gemini-pandoc-lua-filter](https://github.com/kr1sp1n/gemini-pandoc-lua-filter) ⭐ 24 | 🐛 1 | 🌐 Lua | 📅 2020-07-26 (Lua) - lua filter for pandoc to output Gemini text.
* [Html2GeminiPy](https://github.com/Aarontheissueguy/Html2GeminiPy) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2021-02-20 (Python) - Converts Html sites to Gemini sites using markdownify and md2gemini.
* [gemtext2md](https://github.com/mk270/gemtext2md) ⭐ 2 | 🐛 1 | 🌐 Rust | 📅 2023-10-24 (Rust) - tool for converting Gemtext to Markdown
* [gemtext2latex](https://github.com/mk270/gemtext2latex) ⭐ 1 | 🐛 4 | 🌐 Python | 📅 2025-08-18 (Python) - tool for converting Gemtext to reasonable LaTeX and thence PDF
* [gemini-php](https://github.com/YGGverse/gemini-php) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2024-08-02 (PHP) - Composer library for Gemini - includes DokuWiki converter, file-system operations and other API
* [ggemtext](https://github.com/YGGverse/ggemtext) ⭐ 0 | 🐛 1 | 🌐 Rust | 📅 2026-05-12 (Rust) - Glib-oriented Gemtext API
* [gemgen](https://sr.ht/~kota/gemgen/) (Go) - A Markdown to Gemtext generator.
* [gemtexter](https://codeberg.org/snonux/gemtexter) (Bash) - Site generator and blog engine for Gemini. Generates Atom and Gemfeeds , and also does Gemtext to HTML and Markdown conversion.
* [gmi2html](gemini://gemini.thegonz.net/gmi2html.sed) (Sed) - sed script to convert text/gemini to html.
* [gmi-web](https://codeberg.org/talon/gmi-web) (JS) - generate *semantic* HTML styled for readability and mobile-friendliness.
* [gmnhg](https://git.tdem.in/tdemin/gmnhg) (Go) - renders a Hugo site to a Gemini site.
* [md2gmn](https://git.tdem.in/tdemin/gmnhg) (Go) - renders Markdown text to Gemini pages.
* [md2txt](https://codeberg.org/randogoth/md2txt.git) (Python) - converter from Markdown to Gemini text (and other formats) that supports FIGlets, alignment, and margins.
* [gemitwee](https://tildegit.org/smallbird/gemitwee) (PHP) - Converts Twine's Twee2 markup to a set of Gemini files for simple choose-your-own-adventure games.

### Syntax Highlighting

* [gemini.yml](https://github.com/zyedidia/micro/blob/master/runtime/syntax/gemini.yaml) ⭐ 29,444 | 🐛 986 | 🌐 Go | 📅 2026-08-27 - text/gemini syntax highlighting for micro.
* [language\_gmi](https://github.com/lite-xl/lite-xl-plugins/blob/master/plugins/language_gmi.lua) ⭐ 515 | 🐛 124 | 🌐 Lua | 📅 2026-05-06 - gemtext syntax highlighting for lite-xl
* [gemini.kak](https://github.com/kakoune-editor/kakoune-extra-filetypes/blob/master/rc/gemini.kak) ⭐ 30 | 🐛 2 | 🌐 Makefile | 📅 2021-08-06 - text/gemini syntax highlighting for kakoune.
* [gemini.sublime-syntax](https://github.com/adiabatic/gemini.sublime-syntax) ⭐ 9 | 🐛 0 | 🌐 Shell | 📅 2025-10-06 - text/gemini syntax highlighting for bat (and maybe Sublime Text).
* [gemini.nanorc](https://github.com/yzzyx-network/nanorc/blob/master/gemini.nanorc) ⭐ 7 | 🐛 0 | 🌐 Shell | 📅 2020-05-08 - text/gemini syntax highlighting for nano.
* [gemini-intellij-plugin](https://github.com/michael-lazar/gemini-intellij-plugin/) ⭐ 4 | 🐛 0 | 🌐 Java | 📅 2022-12-06 - text/gemini syntax highlighting for IntelliJ IDEs
* [gemini-vim-syntax](https://tildegit.org/sloum/gemini-vim-syntax) - text/gemini syntax highlighting for vim.
* [gemini.el](https://git.carcosa.net/jmcbray/gemini.el) - text/gemini syntax highlighting for emacs.
* [gemini-zed](https://github.com/clseibold/gemini-zed) - text/gemini syntax highlighting for Zed text editor

## Web proxies

* [Mozz.us portal](https://portal.mozz.us/gemini/gemini.circumlunar.space/)
* [Soweli Lukin](https://alexschroeder.ch/soweli-lukin)
* [Vulpes proxy](https://proxy.vulpes.one/gemini/gemini.circumlunar.space/)
* [koyu.space GemProxy](https://gemproxy.koyu.space)
* [Wobbly](https://www.warmedal.se/~wobbly/)
* [Tildeverse Gemini Proxy](https://gemini.tildeverse.org)
* [yah2g: yet another http-to-gemini](https://gem.any-key.press/)

## Bots

* [Fortune Teller Bot](https://github.com/t-900-a/gemini-fortune-bot) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2021-04-20 - Generates a fortune gmi file, gemlog/index.gmi, and atom.xml every time the bot is executed

***

[1]: https://geminiprotocol.net

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
