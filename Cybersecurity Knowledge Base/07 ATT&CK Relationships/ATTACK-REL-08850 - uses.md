---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0154"
target_object: "T1068"
stix_relationship_id: "relationship--412a57f3-ce06-4790-8e3a-cb8c34b9e0f1"
---
# Relationship 8850: S0154 — uses → T1068

**Source object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1068 - Exploitation for Privilege Escalation|T1068: Exploitation for Privilege Escalation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Strike](https://attack.mitre.org/software/S0154) can exploit vulnerabilities such as MS14-058.(Citation: Cobalt Strike TTPs Dec 2017)(Citation: Cobalt Strike Manual 4.3 November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--412a57f3-ce06-4790-8e3a-cb8c34b9e0f1`.
