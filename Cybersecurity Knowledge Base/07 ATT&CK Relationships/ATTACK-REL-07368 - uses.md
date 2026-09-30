---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0446"
target_object: "T1490"
stix_relationship_id: "relationship--3194fa27-46b8-4a05-8d3a-12d7bfe9ad15"
---
# Relationship 7368: S0446 — uses → T1490

**Source object:** [[01 ATT&CK/S0446 - Ryuk|S0446: Ryuk]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ryuk](https://attack.mitre.org/software/S0446) has used vssadmin Delete Shadows /all /quiet to to delete volume shadow copies and vssadmin resize shadowstorage to force deletion of shadow copies created by third-party applications.(Citation: CrowdStrike Ryuk January 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3194fa27-46b8-4a05-8d3a-12d7bfe9ad15`.
