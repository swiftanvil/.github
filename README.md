<!--
  ╔═══════════════════════════════════════════════════════════════╗
  ║                                                               ║
  ║   ⚡  S W I F T   A N V I L  ⚡                               ║
  ║                                                               ║
  ║   forge ▸ stamp ▸ ship                                        ║
  ║                                                               ║
  ╚═══════════════════════════════════════════════════════════════╝
-->

# SwiftAnvil

> **We forge Swift. You ship it.**

SwiftAnvil is a collection of developer tooling packages for the Apple ecosystem —
built with type safety, testability, and AI-friendly scaffolding in mind.

## 🔨 The Forge

| Package | Purpose | Status |
|---------|---------|--------|
| [`anvil-a11y`](https://github.com/swiftanvil/swiftanvil-anvil-a11y) | Type-safe accessibility identifiers | ✅ Stable |
| [`anvil-bench`](https://github.com/swiftanvil/swiftanvil-anvil-bench) | Performance benchmarking toolkit | ✅ Stable |
| [`anvil-strings`](https://github.com/swiftanvil/swiftanvil-anvil-strings) | Type-safe localization | ✅ Stable |
| [`swiftanvil-cli`](https://github.com/swiftanvil/swiftanvil-cli) | CLI scaffolding tool | 🚧 In Progress |

## 🚀 Quick Start

```bash
# Install the CLI
brew install swiftanvil/tap/swiftanvil

# Scaffold a new package
swiftanvil create package --name MyFeature
```

## 🛠️ Using Individual Packages

### Swift Package Manager

```swift
// Package.swift
dependencies: [
    .package(url: "https://github.com/swiftanvil/swiftanvil-anvil-a11y.git", from: "1.0.0"),
    .package(url: "https://github.com/swiftanvil/swiftanvil-anvil-bench.git", from: "1.0.0"),
    .package(url: "https://github.com/swiftanvil/swiftanvil-anvil-strings.git", from: "1.0.0"),
]
```

## 📋 Roadmap

| Milestone | Status | Target |
|-----------|--------|--------|
| v1.0 Core Packages | 🚧 In Progress | Q2 2026 |
| CLI Tooling | 🚧 In Progress | Q2 2026 |
| CI/CD & Automation | 📋 Planned | Q3 2026 |
| Documentation Site | 📋 Planned | Post v1.0 |
| Community Templates | 📋 Planned | Post v1.0 |

> 📝 **Note**: A dedicated documentation website will be built after v1.0 stable release. Until then, all docs live in repo READMEs and GitHub Discussions.

## 🤝 Contributing

We welcome contributions! See our [Contributing Guide](CONTRIBUTING.md) to get started.

## 📜 License

All packages are released under the MIT License.

---

<p align="center">
  <sub>Built with ⚡ by developers, for developers.</sub>
</p>
