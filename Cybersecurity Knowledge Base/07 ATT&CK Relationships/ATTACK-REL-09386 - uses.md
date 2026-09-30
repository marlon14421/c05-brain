---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1559.002"
stix_relationship_id: "relationship--51afbe4e-c5cd-4acd-b4e1-ff7877b78b9e"
---
# Relationship 9386: G0046 — uses → T1559.002

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1559.002 - Dynamic Data Exchange|T1559.002: Dynamic Data Exchange]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) spear phishing campaigns have included malicious Word documents with DDE execution.(Citation: CyberScoop FIN7 Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--51afbe4e-c5cd-4acd-b4e1-ff7877b78b9e`.
