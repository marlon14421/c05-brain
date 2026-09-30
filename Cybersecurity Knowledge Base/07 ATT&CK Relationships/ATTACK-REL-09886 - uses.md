---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1219"
target_object: "T1205.001"
stix_relationship_id: "relationship--23a80f24-8735-40c8-ab6e-c36c04bb1d5a"
---
# Relationship 9886: S1219 — uses → T1205.001

**Source object:** [[01 ATT&CK/S1219 - REPTILE|S1219: REPTILE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205.001 - Port Knocking|T1205.001: Port Knocking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[REPTILE](https://attack.mitre.org/software/S1219) has the ability to control compromised endpoints via port knocking.(Citation: Google Cloud Mandiant UNC3886 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--23a80f24-8735-40c8-ab6e-c36c04bb1d5a`.
