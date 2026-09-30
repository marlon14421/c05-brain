---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1027"
target_object: "T1547.001"
stix_relationship_id: "relationship--b26fc06b-507b-4fbd-bf07-b4e880ac85ab"
---
# Relationship 9090: S1027 — uses → T1547.001

**Source object:** [[01 ATT&CK/S1027 - Heyoka Backdoor|S1027: Heyoka Backdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Heyoka Backdoor](https://attack.mitre.org/software/S1027) can establish persistence with the auto start function including using the value `EverNoteTrayUService`.(Citation: SentinelOne Aoqin Dragon June 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b26fc06b-507b-4fbd-bf07-b4e880ac85ab`.
