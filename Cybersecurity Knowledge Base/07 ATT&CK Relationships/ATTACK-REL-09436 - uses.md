---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0641"
target_object: "T1027"
stix_relationship_id: "relationship--9d11c36e-e738-4d2a-98cf-f5f962a716ea"
---
# Relationship 9436: S0641 — uses → T1027

**Source object:** [[01 ATT&CK/S0641 - Kobalos|S0641: Kobalos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kobalos](https://attack.mitre.org/software/S0641) encrypts all strings using RC4 and bundles all functionality into a single function call.(Citation: ESET Kobalos Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d11c36e-e738-4d2a-98cf-f5f962a716ea`.
