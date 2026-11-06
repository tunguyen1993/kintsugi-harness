# Kintsugi Harness v1.3.0 — Edition & Version Comparison Matrix

## 1. Product Tier Comparison (`Free $0` vs `Tier 1 $15` vs `Tier 2 $19` vs `Tier 3 $29`)

| Capability / Module | Core Guard Free (`$0`) | Tier 1: FinOps & Reliability Pro (`$15`) | Tier 2: Zero-Trust AppSec & MCP Pro (`$19`) | Tier 3: Enterprise Complete Pro (`$29`) |
| :--- | :---: | :---: | :---: | :---: |
| **Curated Core + Exclusive Pro Scars** | 16 Core (`KS-001..016`) | 11 FinOps/Reliability (`KS-018,025,026,030,031` + Core) | 21 AppSec/MCP (`KS-017,019..024,027..029,032` + Core) | **All 32/32 (`KS-001..KS-032`)** |
| **`@KML/1` Symbolic Machine-Language Wire (`scars.kml`)** | 16 rules | **844 `@KML/1` rules** | **862 `@KML/1` rules** | **All 1,706 `@KML/1` rules** |
| **Deterministic Auto-Fix Codemods (`kintsugi autofix --apply`)** | — (Scan only) | **4 Auto-Fix Codemods** | **8 Auto-Fix Codemods** | **All 12/12 Auto-Fix Codemods** |
| **Interactive Slash Workflows (`.claude/commands/*.md`)** | — | 4 Slash Workflows | 4 Slash Workflows | **4 Slash Workflows** |
| **Frontier Collective Pool (`collective_pool_lessons.json`)** | — | 40 Frontier Lessons | 40 Frontier Lessons | **40 Frontier Lessons** |
| **Delivery Formats** | `.zip` | `.zip` + AEAD `.kpack` | `.zip` + AEAD `.kpack` | **`.zip` + AEAD `.kpack`** |

## 2. Version Evolution History (`v0.2.0` -> `v0.9.0` -> `v1.2.0` -> `v1.3.0`)

| Version | Key Architecture Milestone | Corpus Size | Wire Format | Compression & Parse Speed | Security & DLP Gate |
| :--- | :--- | :---: | :---: | :---: | :--- |
| **`v0.2.0`** | Initial static Markdown skill splits | 18 Scars | Human Markdown | Baseline (`0%` wire compression) | Basic regex scan |
| **`v0.3.0`–`v0.9.0`** | Added `KMI/1` header & 14 Exclusive Pro Scars (`KS-019..032`) | 30–32 Scars | JSON + `KMI/1` (` prose `) | `~93%` prompt token savings | 5-Pool Council TP/FP check |
| **`v1.2.0`** | Added `PBKDF2-HMAC-SHA256` `.kpack` AEAD encryption & 40 Frontier Lessons | 30 Curated Scars | Human-prose JSON | `51.8k` chars / `1.81 MB` raw ledger | 6-Layer Shield |
| **`v1.3.0` (Current)** | **Universal Agent Machine Language (`@KML/1`: `@OP/1`, `@TRAP/1`, `@LAW/1`) + Native Rust `kintsugi-rs v1.3.0` + 7-Layer Owner Hidden Seal** | **32 Core+Pro + 1,706 `@KML/1` Evolved Scars** | **`@KML/1` Symbolic AST-IR (`scars.kml`)** | **`96.33%` zlib reduction (`66.5 KB`), `3.28x` faster Python parse, `3.15 ms` Rust parse** | **7-Layer Zero-Trust + Auto-DLP Scrub + Outbound Egress Firewall + Owner Stego/HMAC Seal** |
