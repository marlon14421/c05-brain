---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1588.004"
stix_relationship_id: "relationship--5063d844-fd04-478e-8812-399ba4e7fa58"
---
# Relationship 8517: G1041 — uses → T1588.004

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.004 - Digital Certificates|T1588.004: Digital Certificates]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) created new certificates using a technique called the actors performed "certificate impersonation," a technique in which [Sea Turtle](https://attack.mitre.org/groups/G1041) obtained a certificate authority-signed X.509 certificate from another provider for the same domain imitating the one already used by the targeted organization.(Citation: Talos Sea Turtle 2019)(Citation: Talos Sea Turtle 2019_2)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5063d844-fd04-478e-8812-399ba4e7fa58`.
