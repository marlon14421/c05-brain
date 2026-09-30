---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0502"
target_object: "T1041"
stix_relationship_id: "relationship--a12ce761-4e08-4fcd-b00a-7b5eb082fda4"
---
# Relationship 7516: S0502 — uses → T1041

**Source object:** [[01 ATT&CK/S0502 - Drovorub|S0502: Drovorub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Drovorub](https://attack.mitre.org/software/S0502) can exfiltrate files over C2 infrastructure.(Citation: NSA/FBI Drovorub August 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a12ce761-4e08-4fcd-b00a-7b5eb082fda4`.
