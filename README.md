<div align="center">

# Griffin

**Founder & CEO @Billy**

*Systems Architect · Language Designer · AI Infrastructure*

*"I always hated sleep."*

[![Website](https://img.shields.io/badge/billy-111?style=flat-square&logo=safari&logoColor=white)](https://billylives.com)
[![Medium](https://img.shields.io/badge/Medium-111?style=flat-square&logo=medium&logoColor=white)](https://griffinn.medium.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-111?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/griffincancode)
[![GitHub](https://img.shields.io/badge/98_repos-111?style=flat-square&logo=github&logoColor=white)](https://github.com/griffincancode?tab=repositories)

</div>

---

## Philosophy

Vibe coding before it had a name. Systems programming, language design, AI infrastructure. Convention is a floor, never a ceiling; performance and novel architecture earn the right to break protocol. I have shipped in D, Rust, Go, Haskell, OCaml, Zig, Swift, Nim, Elixir, or whatever the problem demanded.

---

## Published Packages

| Registry | Packages |
|:---|:---|
| **Rust** · crates.io | [bldr](https://crates.io/crates/bldr) · [dei](https://crates.io/crates/dei) · [howmany](https://crates.io/crates/howmany) · [krnchr](https://crates.io/crates/krnchr) · [sherlock-io](https://crates.io/crates/sherlock-io) |
| **Python** · PyPI | [stampede-cache](https://pypi.org/project/stampede-cache/) · [callosum-dsl](https://pypi.org/project/callosum-dsl/) · [toolcase](https://pypi.org/project/toolcase/) · [qvenv](https://pypi.org/project/qvenv/) · [qgit](https://pypi.org/project/qgit/) |
| **JavaScript** · npm | [@retrigger/core](https://www.npmjs.com/package/@retrigger/core) · [sitemind](https://www.npmjs.com/package/sitemind) |
| **VS Code / Cursor** | [howmany](https://marketplace.visualstudio.com/items?itemName=GriffinCanCode.howmany) |
| **Homebrew** | [bldr](https://github.com/griffincancode/homebrew-bldr) · [dei](https://github.com/griffincancode/homebrew-dei) · [howmany](https://github.com/griffincancode/homebrew-howmany) · [builder](https://github.com/griffincancode/homebrew-builder) |

---

## Operating Systems & Infrastructure

### [AgentOS](https://github.com/griffincancode/AgentOS)
> A complete desktop operating system, in userspace.

Microkernel with 95+ syscalls, CFS scheduling, four IPC types, VFS, network isolation. Four layers stack cleanly: Rust kernel, Go services, Python AI, React shell. Window management, dock, app launcher, session restore; the whole apparatus.

`Rust` · `Go` · `Python` · `TypeScript` · `Operating System`

### [bldr](https://github.com/griffincancode/bldr)
> Polyglot build system in D.

28 language handlers, work-stealing scheduler scaling near-linear past 64 cores, three-tier caching, hermetic sandboxing on Linux/macOS/Windows, runtime dependency discovery. Fewer ceremonies than Bazel; gentler curve than Buck2.

`D` · `Build System` · `Monorepo` · [crates.io](https://crates.io/crates/bldr) · [Homebrew](https://github.com/griffincancode/homebrew-bldr) · [bldrapp.org](https://www.bldrapp.org)

### [Polyglot](https://github.com/griffincancode/Polyglot) *(in progress)*
> One process, every language.

A desktop framework that embeds Python, JS, Rust, Java, C++, Lua, Zig, and WASM into one Go-orchestrated process with true parallelism via goroutines. Not Tauri. Not Electron. Something else.

`Go` · `Framework` · `Desktop` · `WASM`

### [Retrigger](https://github.com/griffincancode/Retrigger)
> File watcher for webpack and Vite.

SIMD hashing past 5GB/s, Rust daemon, Zig system watcher, zero-copy Node bindings, sub-5ms event latency.

`Rust` · `Zig` · `Node.js` · `Hot Reload` · [npm](https://www.npmjs.com/package/@retrigger/core)

### [Workaholic](https://github.com/griffincancode/Workaholic)
> A macOS optimizer in Nim.

Heuristic cache scoring, parallel cleaning across browser, dev, and system caches, real-time TUI. Your machine should outwork you.

`Nim` · `System` · `Optimization`

---

## Developer Tools

### [howmany](https://github.com/griffincancode/howmany)
> Codebase analysis you actually want to read.

Parallel processing, incremental caching, beautiful visualizations. Tells you what your code is, not just how many lines. Sees past tokei.

`Rust` · `TypeScript` · `CLI` · [crates.io](https://crates.io/crates/howmany) · [VS Code](https://marketplace.visualstudio.com/items?itemName=GriffinCanCode.howmany) · [Homebrew](https://github.com/griffincancode/homebrew-howmany)

### [SherlockIO](https://github.com/griffincancode/SherlockIO)
> Language detection across 100+ languages, ~98% accuracy.

Two-stage filter cuts dependencies, build artifacts, and IDE clutter. Smart disambiguation handles `.xml` as XML or Maven, `.r` as R or Rebol.

`Rust` · `Tokio` · `Parsing` · [crates.io](https://crates.io/crates/sherlock-io)

### [krnchr](https://github.com/griffincancode/krnchr)
> File aggregator for AI context.

JSON, text, XML, YAML, CSV. Feed the model what matters.

`Rust` · `Tokio` · `Context Engineering` · [crates.io](https://crates.io/crates/krnchr)

### [Dei](https://github.com/griffincancode/Dei)
> God class and god method detector.

Architecture metrics, coupling analysis, circular dependency detection, configurable thresholds. Rayon-parallel; JSON output for CI integration. Rust and C# today, more coming.

`Rust` · `Static Analysis` · `Code Quality` · [crates.io](https://crates.io/crates/dei) · [Homebrew](https://github.com/griffincancode/homebrew-dei)

### [scantron](https://github.com/griffincancode/scantron)
> Universal text scanner. Grep on steroids.

Crawls any text-based file and extracts structured information from custom patterns. Perl backend (Mojolicious), Elm web UI, Rust CLI. Security audits, migration planning, dependency tracking, technical debt; whatever you need to find at scale.

`Rust` · `Perl` · `Elm` · `DevOps`

#### Smaller Tools

| Project | Description | Stack |
|:--------|:------------|:------|
| [Standardize](https://github.com/griffincancode/Standardize) | Multi-language code formatter; tree-sitter parsing, parallel AST transformations | `Rust` |
| [stampede-cache](https://github.com/griffincancode/stampede-cache) | Async caching with request coalescing, thundering herd prevention, semantic similarity | `Python` `C` |
| [QVenv](https://github.com/griffincancode/QVenv) | Python venv with auto requirements detection | `Python` |
| [QGit](https://github.com/griffincancode/QGit) | Quick git workflow optimizer | `Python` |
| [Desktidy](https://github.com/griffincancode/Desktidy) | Desktop automation | `Python` |
| [FaxMachine](https://github.com/griffincancode/FaxMachine) | Smart template injection | `Python` |
| [Generator](https://github.com/griffincancode/Generator) | Quick file and directory scaffolding | `Shell` |
| [howmany-vscode](https://github.com/griffincancode/howmany-vscode) | VS Code extension for howmany | `TypeScript` |
| [howmany-actions](https://github.com/griffincancode/howmany-actions) | GitHub Actions for howmany | `TypeScript` |
| [sitemind](https://github.com/griffincancode/sitemind) | AI-facing manifests for your website | `Go` |

---

## Domain-Specific Languages

### [Callosum](https://github.com/griffincancode/Callosum)
> A DSL for defining AI personalities.

Compiles `.colo` files into system prompts that produce measurably different model behaviors. Provider-agnostic: OpenAI, Anthropic, any LangChain model, custom systems. The corpus callosum bridges the hemispheres; this one bridges the personalities.

`OCaml` · `Python` · `DSL` · [PyPI](https://pypi.org/project/callosum-dsl/)

### [Wolfgang](https://github.com/griffincancode/Wolfgang)
> A functional music DSL in Haskell.

Compose phrases; transpose, invert, retrograde. Output MIDI for DAWs, MusicXML and LilyPond for the engravers. Mousike tekhne, in code.

`Haskell` · `Music` · `MIDI` · `DSL`

### [prism](https://github.com/griffincancode/prism) *(in progress)*
> An AI-first programming language.

Semantic types that carry business meaning, capability-based security, effect tracking, multi-target compilation to native, TypeScript, and WebAssembly. Built for the era when humans and models share a codebase.

`Rust` · `Language Design` · `Compiler`

### [Iconoglott](https://github.com/griffincancode/Iconoglott)
> A real-time visual DSL.

Lexer to parser to evaluator to canvas. Rust rendering, Python accessibility, FastAPI WebSocket server pushing pixels live.

`Rust` · `Python` · `DSL` · `Visual`

---

## AI Platforms & Agents

### [Quorum](https://github.com/griffincancode/Quorum)
> Three models walk into a problem.

Claude, GPT, and Gemini collaborate via an orchestrator that delegates subtasks and synthesizes responses. FastAPI streaming with SSE, React frontend, PostgreSQL persistence, OpenRouter under the hood.

`Python` · `TypeScript` · `FastAPI` · `React`

### [toolcase](https://github.com/griffincancode/toolcase)
> Type-safe tool framework for AI agents.

Pydantic generics, monadic Result types, MCP and HTTP servers, OpenAI/Anthropic/Google converters. Middleware for retry, timeout, circuit breaking, OTLP-distributed tracing.

`Python` · `LangChain` · `Agents` · [PyPI](https://pypi.org/project/toolcase/)

### [Hephaestus](https://github.com/griffincancode/Hephaestus)
> Multi-agent idea engine, named after the Greek god of craftsmanship.

Business, Code, Science, and Technology agents trade insights through a layered UI. SQLite persistence, auto-generated diagrams, domain-themed visualization. Forge what you cannot yet articulate.

`Python` · `Multi-Agent` · `Visualization`

### [good-listener](https://github.com/griffincancode/good-listener)
> Real-time Zoom intelligence.

Audio capture and screen grabbing in Go; Whisper STT, OCR, streaming LLM in Python; ChromaDB remembers. Listens so you can think.

`Go` · `Python` · `ML` · `Agentic`

### [Cognivore](https://github.com/griffincancode/Cognivore)
> Personal knowledge engine.

Electron desktop with Gemini-powered chat, LanceDB vector store, custom in-app browser (Voyager). Ingests PDFs, URLs, YouTube transcripts; cites everything back.

`JavaScript` · `Electron` · `Gemini` · `LanceDB`

### [typist](https://github.com/griffincancode/typist)
> Voice-to-text on macOS, powered by WhisperX.

Glassmorphism floating UI follows your cursor. Apple Silicon and CUDA optimized; fully local inference. ⌘⇧Space and the room types itself.

`Swift` · `Python` · `Whisper` · `STT`

---

## Games & Simulations

| Project | Description | Stack |
|:--------|:------------|:------|
| [BlackholeSim](https://github.com/griffincancode/BlackholeSim) | Black hole simulation with realistic physics and ray tracing | `C++` `OpenGL` `GLSL` |
| [manifest](https://github.com/griffincancode/manifest) *(in development)* | Moddable Civ-style country builder; Rust ECS, Zig SIMD, Lua scripting, Tauri shell | `Rust` `Lua` `Zig` |
| [CopyShaft](https://github.com/griffincancode/CopyShaft) | Minecraft-inspired locally run sandbox | `Java` |
| [Beastlings](https://github.com/griffincancode/Beastlings) | TinyZoo clone with character | `none` |
| [TameImpala](https://github.com/griffincancode/TameImpala) | A very cleverly named game | `JavaScript` |
| [prison-escape-simulation](https://github.com/griffincancode/prison-escape-simulation) | Escape simulation | `JavaScript` |
| [PsychoFlight](https://github.com/griffincancode/PsychoFlight) | Flight game | `JavaScript` |
| [Grandmasters](https://github.com/griffincancode/Grandmasters) | ChatGPT playing dimensionally-modified chess | `Python` |

---

## Research & Visualization

| Project | Description | Stack |
|:--------|:------------|:------|
| [LangViz](https://github.com/griffincancode/LangViz) | Semantic maps of 51 Indo-European languages; FastAPI + pgvector, Perl regexer, Rust phonetics, SvelteKit + D3 | `Python` `Perl` `Rust` |
| [Etymologistics](https://github.com/griffincancode/Etymologistics) *(WIP)* | RAG-driven etymology research and visualization, ChromaDB-backed | `Python` |
| [CompareFaces](https://github.com/griffincancode/CompareFaces) | Mathematical facial structure comparison | `Python` |
| [facekeeper](https://github.com/griffincancode/facekeeper) | Facial recognition embeddings | `Python` |
| [The-Instrument](https://github.com/griffincancode/The-Instrument) | New instrument using computer vision | `Python` |
| [Amplitude](https://github.com/griffincancode/Amplitude) | Instrument teacher demo using ML and CV | `TypeScript` |

---

## Productivity & Apps

| Project | Description | Stack |
|:--------|:------------|:------|
| [Foundry](https://github.com/griffincancode/Foundry) *(early)* | Block editor in Electron; Stage 1 clones Notion. Stage 2 surpasses it. | `JavaScript` |
| [lingua](https://github.com/griffincancode/lingua) | Russian language learning app | `Python` |
| [Building-Blocks](https://github.com/griffincancode/Building-Blocks) | Idea manager, tracker, and discovery system | `Vue` |

---

## Experiments & Fun

| Project | Description | Stack |
|:--------|:------------|:------|
| [SpellingBee](https://github.com/griffincancode/SpellingBee) | NYT spelling bee solver | `Python` |
| [whisps](https://github.com/griffincancode/whisps) | Elixir experiments | `Elixir` |
| [virtual_compass](https://github.com/griffincancode/virtual_compass) | Moral compass for ethical dilemmas | `Python` |
| [Quantum](https://github.com/griffincancode/Quantum) | Half-baked, briefly interesting | `Python` |
| [safespace](https://github.com/griffincancode/safespace) | Environment isolation for testing; filesystem, network, VM | `Python` |
| [OnArrival](https://github.com/griffincancode/OnArrival) | Arrival automation | `Python` |
| [Tenire](https://github.com/griffincancode/Tenire) | Experiments | `Python` |
| [WorldModel](https://github.com/griffincancode/WorldModel) | World modeling sketch | `none` |

---

<div align="center">

*Tools that should not exist, but do. The next one is already in motion.*

</div>
