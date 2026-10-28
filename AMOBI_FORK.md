# Amobi Swift SQLite core package fork

- Upstream: <https://github.com/powersync-ja/powersync-sqlite-core-swift>
- Baseline: `v0.5.3`, commit `0302873677f07039d5e2fc4d1aefdf093e8e6292`
- Source archive SHA-256: `7eea0ff79df8c8b620bb214bbd2524548f853f2567569275f14eda4830505745`
- License: Apache-2.0; upstream LICENSE retained.
- Amobi patches: none yet.

This repository is a SwiftPM wrapper around a binary XCFramework. Its pinned
Package.swift still downloads that framework from the upstream GitHub release;
the actual extension implementation source is in
[`../sqlite_core/`](../sqlite_core/AMOBI_FORK.md).
