---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1194"
target_object: "T1654"
stix_relationship_id: "relationship--9c0b8bff-6cfe-4b12-843c-19985efd2d3b"
---
# Relationship 8203: S1194 — uses → T1654

**Source object:** [[01 ATT&CK/S1194 - Akira _v2|S1194: Akira _v2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1654 - Log Enumeration|T1654: Log Enumeration]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Akira _v2](https://attack.mitre.org/software/S1194) can enumerate the trace, debug, error, info, and warning logs on targeted systems.(Citation: Cisco Akira Ransomware OCT 2024)(Citation: Palo Alto Howling Scorpius DEC 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9c0b8bff-6cfe-4b12-843c-19985efd2d3b`.
