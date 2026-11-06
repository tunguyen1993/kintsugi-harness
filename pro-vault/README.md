# 🔒 Kintsugi Harness Pro Skill Vault (`v1.3.0` — Encrypted `.kpack` Distribution)

The **`opensource`** and **`main`** branches contain the **$0 Free Starter Skill Pack** ([`free-skill-pack/kintsugi-core-guard-free-v1.3.0.zip`](https://github.com/tunguyen1993/kintsugi-harness/tree/opensource/free-skill-pack)) and the **1-Command Live Verification Suite** ([`free-skill-pack/scripts/verify_editions_and_benchmarks.py`](https://github.com/tunguyen1993/kintsugi-harness/blob/main/free-skill-pack/scripts/verify_editions_and_benchmarks.py)), while this **`premium`** branch hosts the **Commercial Pro Skill Packs (`v1.3.0`)** encrypted with **`KPACK1` Authenticated Encryption** (`PBKDF2-HMAC-SHA256` 200,000 iterations + `SHA256-CTR` + `Encrypt-then-HMAC-SHA256`).

See [`EDITION_AND_VERSION_MATRIX.md`](./EDITION_AND_VERSION_MATRIX.md) for the complete comparison between the 4 Editions (`$0` / `$15` / `$19` / `$29`) and versions (`v0.2.0` -> `v0.9.0` -> `v1.2.0` -> `v1.3.0`).

## Product Lineup (`v1.3.0` — `@KML/1` Symbolic Machine Language + 7-Layer Zero-Trust Shield)

| Tier | Bundle / Archive | Scars & `@KML/1` Wire | Auto-Fix Codemods | Price | Access |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Tier 0 (Free Funnel)** | [`free-skill-pack/kintsugi-core-guard-free-v1.3.0.zip`](https://github.com/tunguyen1993/kintsugi-harness/tree/opensource/free-skill-pack) | `16` Core Scars (`KS-001`..`KS-016`) | Preview (`dry-run`) | **`$0` (Free)** | Public on `opensource` & `main` |
| **Tier 1 (Pro)** | `pro-vault/kintsugi-agent-finops-reliability-pro-v1.3.0.kpack` | `11` Scars + `844` `@KML/1` wire records | `4` Live Codemods | **`$15`** | Requires Customer `--license-key` |
| **Tier 2 (Pro)** | `pro-vault/kintsugi-zero-trust-mcp-security-pro-v1.3.0.kpack` | `21` Scars + `862` `@KML/1` wire records | `8` Live Codemods | **`$19`** | Requires Customer `--license-key` |
| **Tier 3 (Enterprise Complete)** | `pro-vault/kintsugi-enterprise-complete-pro-v1.3.0.kpack` | **`32/32` Scars + `1,706` `@KML/1` wire records** | **`12/12` Live Codemods + 4 Slash Commands** | **`$29`** *(Value `$49`, Save 41%)* | Requires Customer `--license-key` |

## Unlock & Install a Pro Pack (With Customer License Key)

```bash
kintsugi install-pack pro-vault/kintsugi-enterprise-complete-pro-v1.3.0.kpack \
  --target ./skills \
  --license-key KPRO-XXXX-XXXXXXXXXXXXXXXX
```
