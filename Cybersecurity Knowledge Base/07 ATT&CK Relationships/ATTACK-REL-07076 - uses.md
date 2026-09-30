---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0250"
target_object: "T1573.002"
stix_relationship_id: "relationship--d9b7596b-185a-4a2f-8559-6b9349f4c9b9"
---
# Relationship 7076: S0250 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0250 - Koadic|S0250: Koadic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Koadic](https://attack.mitre.org/software/S0250) can use SSL and TLS for communications.(Citation: Github Koadic)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9b7596b-185a-4a2f-8559-6b9349f4c9b9`.
