---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0172"
target_object: "T1560.003"
stix_relationship_id: "relationship--98d3455f-49cc-4539-ba35-4b11bec0ddcd"
---
# Relationship 7824: S0172 — uses → T1560.003

**Source object:** [[01 ATT&CK/S0172 - Reaver|S0172: Reaver]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Reaver](https://attack.mitre.org/software/S0172) encrypts collected data with an incremental XOR key prior to exfiltration.(Citation: Palo Alto Reaver Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--98d3455f-49cc-4539-ba35-4b11bec0ddcd`.
