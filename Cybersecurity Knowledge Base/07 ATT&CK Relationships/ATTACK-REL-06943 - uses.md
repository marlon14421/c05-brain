---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9034"
target_object: "T1195.001"
stix_relationship_id: "relationship--35b777b1-2c2e-4f00-bb08-843bc3e42d69"
---
# Relationship 6943: S9034 — uses → T1195.001

**Source object:** [[01 ATT&CK/S9034 - Tsundere Botnet|S9034: Tsundere Botnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1195.001 - Compromise Software Dependencies and Development Tools|T1195.001: Compromise Software Dependencies and Development Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tsundere Botnet](https://attack.mitre.org/software/S9034) has used the Node Package Manager (npm) to download malicious packages and to deliver the payload.(Citation: SecureListUbiedo_Tsundere_Nov2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--35b777b1-2c2e-4f00-bb08-843bc3e42d69`.
