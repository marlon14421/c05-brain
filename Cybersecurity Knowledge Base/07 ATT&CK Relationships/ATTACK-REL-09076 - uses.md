---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1041"
target_object: "T1203"
stix_relationship_id: "relationship--941a9634-bacb-4389-bb17-09212c937683"
---
# Relationship 9076: G1041 — uses → T1203

**Source object:** [[01 ATT&CK/G1041 - Sea Turtle|G1041: Sea Turtle]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sea Turtle](https://attack.mitre.org/groups/G1041) has used exploits for vulnerabilities such as CVE-2021-44228, CVE-2021-21974, and CVE-2022-0847 to achieve client code execution.(Citation: PWC Sea Turtle 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--941a9634-bacb-4389-bb17-09212c937683`.
