---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0010"
target_object: "T1071.001"
stix_relationship_id: "relationship--825aded7-3c93-47ec-9ba5-5bd5af4e2e2b"
---
# Relationship 9237: G0010 — uses → T1071.001

**Source object:** [[01 ATT&CK/G0010 - Turla|G0010: Turla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Turla](https://attack.mitre.org/groups/G0010) has used HTTP and HTTPS for C2 communications.(Citation: ESET Turla Mosquito Jan 2018)(Citation: ESET Turla Mosquito May 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--825aded7-3c93-47ec-9ba5-5bd5af4e2e2b`.
