---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0663"
target_object: "T1543.002"
stix_relationship_id: "relationship--9a0137e5-82d0-4419-961a-9b0eb47b2d79"
---
# Relationship 5522: S0663 — uses → T1543.002

**Source object:** [[01 ATT&CK/S0663 - SysUpdate|S0663: SysUpdate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.002 - Systemd Service|T1543.002: Systemd Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SysUpdate](https://attack.mitre.org/software/S0663) can copy a script to the user owned `/usr/lib/systemd/system/` directory with a symlink mapped to a `root` owned directory, `/etc/ystem/system`, in the unit configuration file's `ExecStart` directive to establish persistence and elevate privileges.(Citation: Lunghi Iron Tiger Linux)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9a0137e5-82d0-4419-961a-9b0eb47b2d79`.
