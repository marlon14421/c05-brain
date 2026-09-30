---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0041"
target_object: "T1689"
stix_relationship_id: "relationship--898120ce-0d97-424b-b0a1-70bfc84767ff"
---
# Relationship 8391: C0041 — uses → T1689

**Source object:** [[01 ATT&CK/C0041 - FrostyGoop Incident|C0041: FrostyGoop Incident]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1689 - Downgrade Attack|T1689: Downgrade Attack]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [FrostyGoop Incident](https://attack.mitre.org/campaigns/C0041), the adversary downgraded firmware on victim devices in order to impair visibility into the process environment.(Citation: Dragos FROSTYGOOP 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--898120ce-0d97-424b-b0a1-70bfc84767ff`.
