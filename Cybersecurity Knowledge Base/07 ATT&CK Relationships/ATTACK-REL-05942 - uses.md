---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0034"
target_object: "T1071"
stix_relationship_id: "relationship--32abb557-d923-4a6d-bda6-79a95063f298"
---
# Relationship 5942: S0034 — uses → T1071

**Source object:** [[01 ATT&CK/S0034 - NETEAGLE|S0034: NETEAGLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071 - Application Layer Protocol|T1071: Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Adversaries can also use [NETEAGLE](https://attack.mitre.org/software/S0034) to establish an RDP connection with a controller over TCP/7519.

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--32abb557-d923-4a6d-bda6-79a95063f298`.
