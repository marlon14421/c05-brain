---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0118"
target_object: "T1543.003"
stix_relationship_id: "relationship--fa2c0697-0d47-4ee9-b5bf-845ac3453c3a"
---
# Relationship 9512: S0118 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0118 - Nidiran|S0118: Nidiran]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Nidiran](https://attack.mitre.org/software/S0118) can create a new service named msamger (Microsoft Security Accounts Manager).(Citation: Symantec Backdoor.Nidiran)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa2c0697-0d47-4ee9-b5bf-845ac3453c3a`.
