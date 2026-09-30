---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1046"
target_object: "T1105"
stix_relationship_id: "relationship--8f025145-ed37-4a29-bf4c-2fb3aa42e1f1"
---
# Relationship 7828: G1046 — uses → T1105

**Source object:** [[01 ATT&CK/G1046 - Storm-1811|G1046: Storm-1811]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-1811](https://attack.mitre.org/groups/G1046) has used scripted `cURL` commands, [BITSAdmin](https://attack.mitre.org/software/S0190), and other mechanisms to retrieve follow-on batch scripts and tools for execution on victim devices.(Citation: Microsoft Storm-1811 2024)(Citation: rapid7-email-bombing)(Citation: RedCanary June Insights 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f025145-ed37-4a29-bf4c-2fb3aa42e1f1`.
