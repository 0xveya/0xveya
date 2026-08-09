# 0xveya

I mostly build systems stuff, backend/infrastructure tools, Python libraries, and things for my own dev setup.

## Projects

<table>
<tr>
<td width="33%" valign="top" align="center">

<img src="./assets/glorp.avif" width="90" alt="tethux logo">

### [tethux](https://github.com/tethux/tethux)

Network emulation toolkit for building programmable Ethernet topologies across containers, VMs, and physical hosts.

<sub>Go · Docker/Virtualization · networking · Linux</sub>

</td>
<td width="33%" valign="top" align="center">

<img src="./assets/ErmGlerm.avif" width="90" alt="go-to-ts logo">

### [go-to-ts](https://github.com/0xveya/go-to-ts)

Converts Go type definitions into TypeScript, including structs, aliases, enums, tags, and nullable SQL types.

<sub>Go · TypeScript · Astro</sub>

</td>
<td width="33%" valign="top" align="center">

<img src="./assets/gleepNerd.avif" width="90" alt="eval-mobile logo">

### [eval-mobile](https://github.com/0xveya/eval-mobile)

Mobile-friendly interface for working with 42 evaluation slots using the 42 API.

<sub>Svelte · TypeScript · 42 API</sub>

</td>
</tr>
</table>

## Systems & 42

### [42-rag-against-the-machine](https://github.com/0xveya/42-rag-against-the-machine)

Local RAG system for searching source-code repositories with Tree-sitter chunking, SQLite FTS5/BM25 retrieval, and local Qwen generation.

<sub>Python · SQLite · Tree-sitter · asyncio</sub>

### [sigma-malloc](https://github.com/0xveya/sigma-malloc)

Custom memory allocator exploring arenas, allocation strategy, and thread safety.

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

## Older stuff

### [gns3util](https://github.com/0xveya/gns3util) - dead

Tooling for deploying and managing multi-user GNS3 lab environments.

I stopped working on it after running into limitations with GNS3. Some of the ideas eventually led to [tethux](https://github.com/tethux/tethux).

<sub>Go · GNS3 · networking</sub>
