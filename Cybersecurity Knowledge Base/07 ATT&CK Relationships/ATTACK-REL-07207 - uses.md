---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0050"
target_object: "T1555.003"
stix_relationship_id: "relationship--62943e4f-a181-4eb2-84a4-27ed3e7308af"
---
# Relationship 7207: S0050 — uses → T1555.003

**Source object:** [[01 ATT&CK/S0050 - CosmicDuke|S0050: CosmicDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CosmicDuke](https://attack.mitre.org/software/S0050) collects user credentials, including passwords, for various programs including Web browsers.(Citation: F-Secure The Dukes)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62943e4f-a181-4eb2-84a4-27ed3e7308af`.
