---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0341"
target_object: "T1203"
stix_relationship_id: "relationship--6706d89e-27dd-48bb-ae0b-db51e07cbc91"
---
# Relationship 5127: S0341 — uses → T1203

**Source object:** [[01 ATT&CK/S0341 - Xbash|S0341: Xbash]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Xbash](https://attack.mitre.org/software/S0341) can attempt to exploit known vulnerabilities in Hadoop, Redis, or ActiveMQ when it finds those services running in order to conduct further execution.(Citation: Unit42 Xbash Sept 2018)(Citation: Trend Micro Xbash Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6706d89e-27dd-48bb-ae0b-db51e07cbc91`.
