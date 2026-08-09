# 🌌 QuantumSeed

> A local-first Minecraft seed discovery, analysis, mapping, and navigation toolkit.

QuantumSeed is a modern, high-performance Minecraft seed exploration app designed to do more than display the results of a single seed.

Instead of manually checking seeds one at a time, QuantumSeed lets players define the world they want and search thousands—or millions—of seeds locally using the available power of their computer.

Find rare biome combinations, structures near spawn, unusual terrain formations, partially submerged mansions, ideal survival locations, and more.

QuantumSeed is inspired by the usefulness of tools such as Chunkbase while aiming to provide a more powerful, customizable, and modern experience.

> **QuantumSeed does not use quantum computing.** The name represents exploring many possible world outcomes and narrowing them toward the best result.

---

## ✨ Planned Features

### 🔍 Parallel Seed Discovery

Search multiple Minecraft seeds at the same time using a local multithreaded search engine.

- Uses a configurable number of CPU worker threads
- Automatically detects available system resources
- Supports a recommended minimum of four worker threads
- Pause, resume, cancel, and save search sessions
- View progress, speed, elapsed time, and estimated search size
- Search randomly generated seeds or user-provided seed ranges
- Run multiple search profiles with different goals
- Export promising seeds for later analysis

QuantumSeed is designed to scale based on the user's hardware rather than relying on a remote server.

---

### 🎯 Goal-Based Seed Searching

Describe the kind of world you want and let QuantumSeed rank potential seeds based on how closely they match.

Example goals:

- Woodland mansion partially located in an ocean
- Village within a specific distance of spawn
- Multiple villages near a large plains biome
- Stronghold close to spawn
- Ancient City beneath a specific terrain type
- Mushroom Fields near useful early-game biomes
- Several structures within a chosen radius
- Rare biome combinations
- Specific structures near coordinates
- Flat terrain suitable for building
- A large island surrounded by ocean
- Multiple monuments within a search area
- A survival-friendly spawn with nearby resources

A search can contain several requirements at once:

```text
Find a seed with:

- A village within 500 blocks of spawn
- A plains biome larger than 300 × 300 blocks
- A Woodland Mansion within 2,000 blocks
- An ocean touching the mansion
- A stronghold within 1,500 blocks
- No large mountains within 300 blocks of spawn
