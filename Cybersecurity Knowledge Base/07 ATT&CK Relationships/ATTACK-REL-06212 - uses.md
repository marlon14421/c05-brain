---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0595"
target_object: "T1622"
stix_relationship_id: "relationship--e711d51c-94d3-4a20-ae11-d3584bae36d9"
---
# Relationship 6212: S0595 — uses → T1622

**Source object:** [[01 ATT&CK/S0595 - ThiefQuest|S0595: ThiefQuest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1622 - Debugger Evasion|T1622: Debugger Evasion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ThiefQuest](https://attack.mitre.org/software/S0595) uses a function named is_debugging to perform anti-debugging logic. The function invokes sysctl checking the returned value of P_TRACED . [ThiefQuest](https://attack.mitre.org/software/S0595) also calls ptrace with the PTRACE_DENY_ATTACH flag to prevent debugging.(Citation: wardle evilquest partii)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e711d51c-94d3-4a20-ae11-d3584bae36d9`.
