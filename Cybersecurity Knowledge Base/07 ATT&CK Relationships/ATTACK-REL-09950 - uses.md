---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1227"
target_object: "T1001.003"
stix_relationship_id: "relationship--354a4208-0d17-47ab-bf0d-8611c5ad23e5"
---
# Relationship 9950: S1227 — uses → T1001.003

**Source object:** [[01 ATT&CK/S1227 - StarProxy|S1227: StarProxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.003 - Protocol or Service Impersonation|T1001.003: Protocol or Service Impersonation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StarProxy](https://attack.mitre.org/software/S1227) has utilized TLS record headers in network packets to impersonate various versions of TLS protocols to blend in with legitimate network traffic. [StarProxy](https://attack.mitre.org/software/S1227) used FakeTLS to communicate with its C2 server.(Citation: Zscaler)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--354a4208-0d17-47ab-bf0d-8611c5ad23e5`.
