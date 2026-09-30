---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0093"
target_object: "T1133"
stix_relationship_id: "relationship--57b4f42b-02e2-4cee-98f0-d6935c1e2c7b"
---
# Relationship 7429: G0093 — uses → T1133

**Source object:** [[01 ATT&CK/G0093 - GALLIUM|G0093: GALLIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1133 - External Remote Services|T1133: External Remote Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GALLIUM](https://attack.mitre.org/groups/G0093) has used VPN services, including SoftEther VPN, to access and maintain persistence in victim environments.(Citation: Cybereason Soft Cell June 2019)(Citation: Microsoft GALLIUM December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--57b4f42b-02e2-4cee-98f0-d6935c1e2c7b`.
