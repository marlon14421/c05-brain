---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0094"
target_object: "T1105"
stix_relationship_id: "relationship--7282eabe-73e0-4a10-824b-f18df7f892e2"
---
# Relationship 5941: S0094 — uses → T1105

**Source object:** [[01 ATT&CK/S0094 - Trojan.Karagany|S0094: Trojan.Karagany]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Trojan.Karagany](https://attack.mitre.org/software/S0094) can upload, download, and execute files on the victim.(Citation: Symantec Dragonfly)(Citation: Secureworks Karagany July 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7282eabe-73e0-4a10-824b-f18df7f892e2`.
