---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0681"
target_object: "T1620"
stix_relationship_id: "relationship--cce28b98-698e-4c0b-b625-78b125cf8837"
---
# Relationship 6290: S0681 — uses → T1620

**Source object:** [[01 ATT&CK/S0681 - Lizar|S0681: Lizar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lizar](https://attack.mitre.org/software/S0681) has used the Reflective DLL injection module from Github to inject itself into a process’s memory.(Citation: SekoiaBourhis_DiceLoader_Feb2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cce28b98-698e-4c0b-b625-78b125cf8837`.
