---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0012"
target_object: "T1055.001"
stix_relationship_id: "relationship--7d020981-51b3-4ff6-825f-7cd192c934e1"
---
# Relationship 6285: S0012 — uses → T1055.001

**Source object:** [[01 ATT&CK/S0012 - PoisonIvy|S0012: PoisonIvy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.001 - Dynamic-link Library Injection|T1055.001: Dynamic-link Library Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PoisonIvy](https://attack.mitre.org/software/S0012) can inject a malicious DLL into a process.(Citation: FireEye Poison Ivy)(Citation: Symantec Darkmoon Aug 2005)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7d020981-51b3-4ff6-825f-7cd192c934e1`.
