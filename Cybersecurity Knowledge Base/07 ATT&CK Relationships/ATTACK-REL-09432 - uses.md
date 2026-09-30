---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0053"
target_object: "T1584.008"
stix_relationship_id: "relationship--04885879-10a9-4d12-b9f5-08bfae9da800"
---
# Relationship 9432: C0053 — uses → T1584.008

**Source object:** [[01 ATT&CK/C0053 - FLORAHOX Activity|C0053: FLORAHOX Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1584.008 - Network Devices|T1584.008: Network Devices]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FLORAHOX Activity](https://attack.mitre.org/campaigns/C0053) has compromised network routers and IoT devices for the ORB network.(Citation: ORB Mandiant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04885879-10a9-4d12-b9f5-08bfae9da800`.
