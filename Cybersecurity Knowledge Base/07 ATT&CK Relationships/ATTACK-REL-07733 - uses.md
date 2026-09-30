---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0377"
target_object: "T1574.006"
stix_relationship_id: "relationship--d3102278-dab8-485c-9cd2-52f80c4da8bd"
---
# Relationship 7733: S0377 — uses → T1574.006

**Source object:** [[01 ATT&CK/S0377 - Ebury|S0377: Ebury]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.006 - Dynamic Linker Hijacking|T1574.006: Dynamic Linker Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

When [Ebury](https://attack.mitre.org/software/S0377) is running as an OpenSSH server, it uses LD_PRELOAD to inject its malicious shared module in to programs launched by SSH sessions. [Ebury](https://attack.mitre.org/software/S0377) hooks the following functions from `libc` to inject into subprocesses; `system`, `popen`, `execve`, `execvpe`, `execv`, `execvp`, and `execl`.(Citation: ESET Ebury Oct 2017)(Citation: ESET Ebury May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3102278-dab8-485c-9cd2-52f80c4da8bd`.
