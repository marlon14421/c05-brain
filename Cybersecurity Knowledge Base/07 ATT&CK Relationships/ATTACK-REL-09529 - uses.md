---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1553.002"
stix_relationship_id: "relationship--081c68ae-de26-4ab4-9108-5c7493f34f43"
---
# Relationship 9529: G0046 — uses → T1553.002

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) has signed [Carbanak](https://attack.mitre.org/software/S0030) payloads with legally purchased code signing certificates. [FIN7](https://attack.mitre.org/groups/G0046) has also digitally signed their phishing documents, backdoors and other staging tools to bypass security controls.(Citation: FireEye CARBANAK June 2017)(Citation: FireEye FIN7 Aug 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--081c68ae-de26-4ab4-9108-5c7493f34f43`.
