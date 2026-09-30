---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1011"
target_object: "T1564"
stix_relationship_id: "relationship--d507bcd4-bd22-4d39-b098-20c109ee9cda"
---
# Relationship 7255: S1011 — uses → T1564

**Source object:** [[01 ATT&CK/S1011 - Tarrask|S1011: Tarrask]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564 - Hide Artifacts|T1564: Hide Artifacts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tarrask](https://attack.mitre.org/software/S1011) is able to create “hidden” scheduled tasks by deleting the Security Descriptor (`SD`) registry value.(Citation: Tarrask scheduled task)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d507bcd4-bd22-4d39-b098-20c109ee9cda`.
