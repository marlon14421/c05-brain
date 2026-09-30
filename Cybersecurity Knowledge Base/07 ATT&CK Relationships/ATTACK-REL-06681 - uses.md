---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0280"
target_object: "T1082"
stix_relationship_id: "relationship--47b7e027-4208-4ed6-b4ae-46941fed16be"
---
# Relationship 6681: S0280 — uses → T1082

**Source object:** [[01 ATT&CK/S0280 - MirageFox|S0280: MirageFox]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirageFox](https://attack.mitre.org/software/S0280) can collect CPU and architecture information from the victim’s machine.(Citation: APT15 Intezer June 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--47b7e027-4208-4ed6-b4ae-46941fed16be`.
