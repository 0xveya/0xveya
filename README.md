# 0xveya

I mostly write Go, C++, and C, building systems stuff, backend/infrastructure tools, and things for my own dev setup, along with Python libraries and the occasional slop web app.

## Projects

<img src="./assets/glorp.avif" width="90" alt="tethux logo">

### [tethux](https://github.com/tethux/tethux)

Early-stage network emulation toolkit for programmable Ethernet topologies across containers, VMs, and physical hosts, with Shitnet endpoints and embedded Dynamips routers.

<sub>Go · Docker/Virtualization · networking · Linux</sub>

<img src="./assets/briotap.svg" width="90" alt="briotap icon">

### [briotap](https://github.com/0xveya/briotap)

Go package browser for reading versioned API docs and source, exploring dependency graphs, and checking licenses and security advisories. Inspired by npmx. [Open the app](https://pkgs.saygex.xyz/).

<sub>SvelteKit · TypeScript · Bun · PostgreSQL</sub>

<img src="./assets/teletext.png" width="90" alt="Teletext icon">

### [ORF Teletext client & archive](https://github.com/0xveya/teletext)

Independent Teletext reader and phone PWA, with a Go collector and a searchable historical archive for reading old pages and exploring text and advertising data. [Open the app](https://autism.saygex.xyz).

<sub>Svelte · TypeScript · Go · PostgreSQL</sub>


<details>
<summary>More web apps</summary>

### [go-to-ts](https://github.com/0xveya/go-to-ts)

Converts Go type definitions into TypeScript, including structs, aliases, enums, tags, and nullable SQL types.

<sub>Go · TypeScript · Astro</sub>

### [eval-mobile](https://github.com/0xveya/eval-mobile)

Mobile-friendly interface for working with 42 evaluation slots using the 42 API.

<sub>Svelte · TypeScript · 42 API</sub>

</details>

## Systems & 42

### [dynamips-downgrade](https://github.com/tethux/dynamips-downgrade)

Porting and reworking Dynamips' Cisco router emulation in C++23 for Tethux, including a new MIPS64 JIT, guest memory, and device model. The new execution path runs real Cisco IOS through image decompression; further boot support is still in progress. Includes native modules, typed embedding APIs, and Go bindings.

<sub>C++23 · Cisco emulation · MIPS64 · JIT · xmake</sub>

### [shitnet](https://github.com/tethux/shitnet)

Small userspace network stack with Ethernet, ARP, IPv4, and ICMP support, a C API, Go bindings, and an interactive REPL.

<sub>C++23 · Go · networking · xmake</sub>

### [Nuxe](https://github.com/0xveya/Nuxe)

Unfinished C++23 rewrite of a FromSoftware game-data unpacker, focused on faster decryption and extraction on Linux. The rewrite is still local and has not been pushed to the linked fork yet.

<sub>C++23 · native modules · OpenSSL · xmake</sub>

### [sigma-c-crimes](https://github.com/0xveya/sigma-c-crimes)

Guide to my experimental C23 ecosystem: [sigma_libft](https://github.com/0xveya/sigma_libft), [sigma_rt](https://github.com/0xveya/sigma_rt), and [sigma-malloc](https://github.com/0xveya/sigma-malloc). Bounded data, ownership experiments, macros, and small composable libraries.

<sub>C23 · systems · learning experiments</sub>

### [42-rag-against-the-machine](https://github.com/0xveya/42-rag-against-the-machine)

Local RAG system for searching source-code repositories with Tree-sitter chunking, SQLite FTS5/BM25 retrieval, and local Qwen generation.

<sub>Python · SQLite · Tree-sitter · asyncio</sub>

### [sigma-malloc](https://github.com/0xveya/sigma-malloc)

Experimental allocator library with slabs, buddy allocation, arenas, and ownership diagnostics.

<sub>C · memory · concurrency</sub>

<details>
<summary>More systems & 42 projects</summary>

### [42-codexion](https://github.com/0xveya/42-codexion)

Concurrent simulation focused on scheduling, synchronization, and shared resources.

<sub>C · pthreads · scheduling</sub>

### [42-fly-in](https://github.com/0xveya/42-fly-in)

42 project focused on solving and algorithmic work.

<sub>C · algorithms</sub>

### [A-Maze-ing](https://github.com/Valentins-and-Veyas-42-group-projects/A-Maze-ing)

Maze generation, solving, and terminal visualization.

<sub>Python · algorithms · group project</sub>

### [pac-man](https://github.com/Valentins-and-Veyas-42-group-projects/pac-man)

42 group project with Valentin.

<sub>Python · group project · work in progress</sub>

### [push_swap](https://github.com/Valentins-and-Veyas-42-group-projects/push_swap)

<sub>C · algorithms · group project</sub>

</details>

## Python Libraries

<details>
<summary>Small typed Python libraries</summary>

Small libraries extracted from patterns I kept reusing across projects.

### [typed-errs](https://github.com/0xveya/typed-errs)

Typed `Result` and `Option` values for explicit error handling.

### [typed-concurrency](https://github.com/0xveya/typed-concurrency)

Typed structured concurrency with Go-ish `asyncio` ergonomics: task groups,
channels, threads, and process-pool work.

### [python-crimes](https://github.com/0xveya/python-crimes)

Composable pipes, deferred cleanup, and typed-errs-aware pattern matching.

### [typed-file-io](https://github.com/0xveya/typed-file-io)

Typed text and JSON I/O with validation and callback-based writers.

### [fsnotify-python](https://github.com/0xveya/fsnotify-python)

Recursive Linux filesystem watcher with synchronous and `asyncio` APIs built directly on inotify.

### [sqlite-callback-store](https://github.com/0xveya/sqlite-callback-store)

Small SQLite layer using typed read and transaction callbacks with automatic commit and rollback.

### [cli-fw](https://github.com/0xveya/cli-fw)

Dataclass-driven CLI framework with typed arguments, nested commands, generated help, and parse errors.

</details>

## Developer Tooling

<details>
<summary>Neovim, Nushell & other dev tools</summary>

### [dogshitnorm.nvim](https://github.com/0xveya/dogshitnorm.nvim)

Neovim tooling around 42 formatting and workflow checks.

### [go-mono-repo](https://github.com/0xveya/go-mono-repo)

Neovim plugin for scoping file search, grep, symbols, and route handlers to individual Go monorepo entrypoints.

### [sqlc.nvim](https://github.com/0xveya/sqlc.nvim)

Neovim integration for `sqlc` workflows.

### [nushell-hist-thing](https://github.com/0xveya/nushell-hist-thing)

Per-session, Zsh-like Ctrl+R history search for Nushell.

</details>

### [evil_intra_scraper](https://github.com/0xveya/evil_intra_scraper)

Explore 42 project evaluation data with OAuth, streamed results, and cached API responses.

<sub>Svelte · TypeScript · Valkey · 42 API</sub>

## Older stuff

### [gns3util](https://github.com/0xveya/gns3util) - dead

Tooling for deploying and managing multi-user GNS3 lab environments.

I stopped working on it after running into limitations with GNS3. Some of the ideas eventually led to [tethux](https://github.com/tethux/tethux).

<sub>Go · GNS3 · networking</sub>
