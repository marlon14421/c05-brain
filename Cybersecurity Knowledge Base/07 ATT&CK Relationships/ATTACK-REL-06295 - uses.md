---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0567"
target_object: "T1543.003"
stix_relationship_id: "relationship--372ff318-25a5-476b-9090-7e0fd4534325"
---
# Relationship 6295: S0567 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0567 - Dtrack|S0567: Dtrack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Dtrack](https://attack.mitre.org/software/S0567) can add a service called WBService to establish persistence.(Citation: CyberBit Dtrack)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--372ff318-25a5-476b-9090-7e0fd4534325`.
