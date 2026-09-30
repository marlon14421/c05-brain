---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0373"
target_object: "T1204.002"
stix_relationship_id: "relationship--3683548e-0331-4407-98b0-82253efc0b09"
---
# Relationship 8077: S0373 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0373 - Astaroth|S0373: Astaroth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Astaroth](https://attack.mitre.org/software/S0373) has used malicious files including VBS, LNK, and HTML for execution.(Citation: Securelist Brazilian Banking Malware July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3683548e-0331-4407-98b0-82253efc0b09`.
