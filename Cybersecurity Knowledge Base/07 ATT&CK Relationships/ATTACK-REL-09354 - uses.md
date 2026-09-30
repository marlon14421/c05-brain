---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0396"
target_object: "T1497.001"
stix_relationship_id: "relationship--4ce1ed77-dc5d-42d8-838e-b927dc6d6afb"
---
# Relationship 9354: S0396 — uses → T1497.001

**Source object:** [[01 ATT&CK/S0396 - EvilBunny|S0396: EvilBunny]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1497.001 - System Checks|T1497.001: System Checks]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EvilBunny](https://attack.mitre.org/software/S0396)'s dropper has checked the number of processes and the length and strings of its own file name to identify if the malware is in a sandbox environment.(Citation: Cyphort EvilBunny Dec 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ce1ed77-dc5d-42d8-838e-b927dc6d6afb`.
