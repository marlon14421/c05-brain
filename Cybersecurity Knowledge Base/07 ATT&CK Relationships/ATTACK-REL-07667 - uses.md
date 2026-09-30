---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1016"
target_object: "T1036.005"
stix_relationship_id: "relationship--f5ce003c-c220-4c19-a45f-b2e2a6e924e2"
---
# Relationship 7667: G1016 — uses → T1036.005

**Source object:** [[01 ATT&CK/G1016 - FIN13|G1016: FIN13]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN13](https://attack.mitre.org/groups/G1016) has masqueraded WAR files to look like legitimate packages such as, wsexample.war, wsexamples.com, examples.war, and exampl3s.war.(Citation: Sygnia Elephant Beetle Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5ce003c-c220-4c19-a45f-b2e2a6e924e2`.
