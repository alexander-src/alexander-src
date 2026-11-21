### Alexander (`alexander-src`)

Systems and AI-native software engineer building low-level tooling in Rust and C++20, paired with upfront specifications and compiler-grounded verification.

- **Portfolio & Printable CV:** [alexander-src.github.io](https://alexander-src.github.io)
- **Contact:** [alex.laros@proton.me](mailto:alex.laros@proton.me)
- **Featured Work:**
  - **[`isa-audit`](https://github.com/alexander-src/isa-audit)** ([`v0.2.0`](https://github.com/alexander-src/isa-audit/releases/tag/v0.2.0)): Zero-dependency, `#![forbid(unsafe_code)]` Rust x86-64 ELF64 binary ISA auditor, binary `diff` regression gate, and prebuilt Linux/macOS/Windows CLI (281.6 MiB/s decode throughput, SARIF 2.1.0, GCC ground-truth verified).
  - **[`bincompat`](https://github.com/alexander-src/bincompat)**: Zero-dependency, `#![forbid(unsafe_code)]` Rust ELF64 Linux binary portability CI gate mapping `GLIBC`/`GLIBCXX` version ceilings, `GLIBC_ABI_DT_RELR` tags, and `DT_NEEDED`/`RPATH` constraints to exact undefined symbols (GNU `readelf` ground-truth verified).
  - **[`alexander-src.github.io`](https://github.com/alexander-src/alexander-src.github.io)**: Archival technical portfolio, `isa-audit` engineering case study, and ATS-ready 1-page printable CV.
- **Open-Source Contributions:**
  - **[`boykopovar/AnyPS5#24623`](https://github.com/boykopovar/AnyPS5/pull/24623)** *(merged)*: Cut `tools/env_reference.py` scan runtime from `50.56s` to `3.92s` (~13x speedup) across 7,766 C++ files with SHA-256 byte-identical output.
  - Active contributor across Rust and C++20 tooling (`boykopovar/AnyPS5`, `oxc-project/oxc`).
