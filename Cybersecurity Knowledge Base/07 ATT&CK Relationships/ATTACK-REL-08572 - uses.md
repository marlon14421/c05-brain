---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0061"
target_object: "T1588.003"
stix_relationship_id: "relationship--3b72eb79-c499-4f2a-b6aa-464bb3bbd42d"
---
# Relationship 8572: G0061 — uses → T1588.003

**Source object:** [[01 ATT&CK/G0061 - FIN8|G0061: FIN8]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.003 - Code Signing Certificates|T1588.003: Code Signing Certificates]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN8](https://attack.mitre.org/groups/G0061) has used an expired open-source X.509 certificate for testing in the OpenSSL repository, to connect to actor-controlled C2 servers.(Citation: Bitdefender Sardonic Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3b72eb79-c499-4f2a-b6aa-464bb3bbd42d`.
