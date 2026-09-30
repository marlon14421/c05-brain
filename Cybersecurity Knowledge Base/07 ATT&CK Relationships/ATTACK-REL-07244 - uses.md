---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0484"
target_object: "T1555.003"
stix_relationship_id: "relationship--fafa8b19-211d-4878-9d80-2126e1604b68"
---
# Relationship 7244: S0484 — uses → T1555.003

**Source object:** [[01 ATT&CK/S0484 - Carberp|S0484: Carberp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Carberp](https://attack.mitre.org/software/S0484)'s passw.plug plugin can gather passwords saved in Opera, Internet Explorer, Safari, Firefox, and Chrome.(Citation: Prevx Carberp March 2011)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fafa8b19-211d-4878-9d80-2126e1604b68`.
