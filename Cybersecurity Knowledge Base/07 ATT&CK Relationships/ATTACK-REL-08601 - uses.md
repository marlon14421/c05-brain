---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1665"
stix_relationship_id: "relationship--7cde9b70-5de6-4aed-be28-27072987f2e8"
---
# Relationship 8601: S1111 — uses → T1665

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1665 - Hide Infrastructure|T1665: Hide Infrastructure]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) command and control includes hard-coded domains in the malware masquerading as legitimate services such as Akamai CDN or Amazon Web Services.(Citation: Trellix Darkgate 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7cde9b70-5de6-4aed-be28-27072987f2e8`.
