---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1051"
target_object: "T1140"
stix_relationship_id: "relationship--43c68bb8-28e2-4ee0-91aa-ffc16dcc45bc"
---
# Relationship 8160: S1051 — uses → T1140

**Source object:** [[01 ATT&CK/S1051 - KEYPLUG|S1051: KEYPLUG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KEYPLUG](https://attack.mitre.org/software/S1051) can decode its configuration file to determine C2 protocols.(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43c68bb8-28e2-4ee0-91aa-ffc16dcc45bc`.
