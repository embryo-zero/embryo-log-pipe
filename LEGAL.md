# Legal notes for Embryo Log Pipe

Embryo Log Pipe is a modified version of **vector** (https://github.com/vectordotdev/vector), copyright its authors.
License (read from its license file on 2026-11-17): **MPL-2.0**. Original license files, unchanged: LICENSE, LICENSE-3rdparty.csv, NOTICE, license-tool.toml.

- `LICENSE`: Mozilla Public License, version 2.0 / 1. Definitions / 1.1. "Contributor"
- `LICENSE-3rdparty.csv`: Component,Origin,License,Copyright / adler2,https://github.com/oyvindln/adler2,0BSD OR MIT OR Apache-2.0,"Jonas Schievink <jonasschievink@gmail.com>, oyvindln <oyvindln@users.noreply.github.com>" / ae
- `NOTICE`: Unless explicitly stated otherwise all files in this repository are licensed under the Mozilla / Public License, version 2.0 (MPL-2.0). / This product includes software developed at Datadog (https://w
- `license-tool.toml`: [overrides] / "backon" = { origin = "https://github.com/Xuanwo/backon" } / "bollard-stubs" = { origin = "https://github.com/fussybeaver/bollard" }

"vector" is the original project's name; ours is Embryo Log Pipe, "based on vector". We do not use their names or logos to promote ours.

## When we offer it to people
- MPL-2.0: changed MPL files stay MPL and their source goes with copies; keep notices.
- More than one license file: `LICENSE-3rdparty.csv` reads as CHECK (not recognised); `license-tool.toml` reads as CHECK (not recognised). CHECK which parts each covers.
- Bundled third-party parts keep their own licenses: CHECK them before a release.
- What people make with the tool belongs to them; the tool's license does not cover its output.
- No warranty beyond what the license says.
