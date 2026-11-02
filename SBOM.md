# Source SBOM

**Initial source snapshot, not a release report.** Source commit `8aa903085479910c77de95f7e7c178f66a245ed3` predates the tooling commit. Future release reports use exact published tags.

Source repository inventory only; completeness is UNKNOWN. Syft inventories tracked source/package manifests. Gitlinks and declared vendored/model evidence are inspected at immutable pins. CMake declarations are conditional requirements, not resolved installations. This is NOT proof of operating-system packages, static-link closure, build-time resolution, or the contents of release binaries.

Generation: **success**

## Source identity

wave-owl/wsprd `8aa903085479910c77de95f7e7c178f66a245ed3`

- sbom:role: source-root
- sbom:git-commit: 8aa903085479910c77de95f7e7c178f66a245ed3
- sbom:git-tree: 4b482f7bd6d46d300f7fb6bbdae5031e28d1b0d6
- sbom:source-repository: https://github.com/wave-owl/wsprd
- sbom:release-tags: []
- sbom:license-evidence: [{"path": "COPYING", "sha256": "b4bbff835ca86b6051284a77138b7b31db215fb3e8aa70221464126cc9ad60fa"}]
- sbom:license-resolution: unresolved; manual review required

## Generation errors

None.

## Components and unresolved licenses

| Component | Version | Role | License |
| --- | --- | --- | --- |
| wave-owl/wsprd | 8aa903085479910c77de95f7e7c178f66a245ed3 | source-root | unresolved; manual review required |
| pffft.c | unresolved | declared-vendored-source | unresolved; manual review required |
| pffft.h | unresolved | declared-vendored-source | unresolved; manual review required |
| Conditional source requirements declared by Makefile | unresolved | conditional-build-runtime-requirement | unresolved |
| C/Fortran toolchain; Makefile | unresolved | conditional-build-runtime-requirement | unresolved |

License evidence paths/hashes, source manifests, model hashes and conditional
CMake declarations are recorded in SBOM.cdx.json. Declared upstream pins do not
prove vendored equivalence. No dependency installation or build was performed.
