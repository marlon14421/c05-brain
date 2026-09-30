---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1040"
target_object: "T1657"
stix_relationship_id: "relationship--f0cd78a8-82ce-47e8-9ecc-beaaf34248c2"
---
# Relationship 9270: G1040 — uses → T1657

**Source object:** [[01 ATT&CK/G1040 - Play|G1040: Play]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1657 - Financial Theft|T1657: Financial Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Play](https://attack.mitre.org/groups/G1040) demands ransom payments from victims to unencrypt filesystems and to not publish sensitive data exfiltrated from victim networks.(Citation: CISA Play Ransomware Advisory December 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0cd78a8-82ce-47e8-9ecc-beaaf34248c2`.
