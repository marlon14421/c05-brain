---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1204.002"
stix_relationship_id: "relationship--b13de0c7-196c-4a74-9b91-c7c8c4cce419"
---
# Relationship 7572: S1111 — uses → T1204.002

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) initial infection payloads can masquerade as pirated media content requiring user interaction for code execution.(Citation: Ensilo Darkgate 2018) [DarkGate](https://attack.mitre.org/software/S1111) is distributed through phishing links to VBS or MSI objects requiring user interaction for execution.(Citation: Trellix Darkgate 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b13de0c7-196c-4a74-9b91-c7c8c4cce419`.
