---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0280"
target_object: "T1059.003"
stix_relationship_id: "relationship--c6dc9631-b324-47d1-8bbd-975d20fa5e58"
---
# Relationship 6758: S0280 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0280 - MirageFox|S0280: MirageFox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirageFox](https://attack.mitre.org/software/S0280) has the capability to execute commands using cmd.exe.(Citation: APT15 Intezer June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c6dc9631-b324-47d1-8bbd-975d20fa5e58`.
