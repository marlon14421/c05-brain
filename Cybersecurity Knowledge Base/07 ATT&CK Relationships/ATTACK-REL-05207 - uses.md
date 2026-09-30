---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0065"
target_object: "T1074.002"
stix_relationship_id: "relationship--bbd420ed-6959-4190-8317-2b9ecdc32856"
---
# Relationship 5207: G0065 — uses → T1074.002

**Source object:** [[01 ATT&CK/G0065 - Leviathan|G0065: Leviathan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.002 - Remote Data Staging|T1074.002: Remote Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Leviathan](https://attack.mitre.org/groups/G0065) has staged data remotely prior to exfiltration.(Citation: CISA AA21-200A APT40 July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bbd420ed-6959-4190-8317-2b9ecdc32856`.
