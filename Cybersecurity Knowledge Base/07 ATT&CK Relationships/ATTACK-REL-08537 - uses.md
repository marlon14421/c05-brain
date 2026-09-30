---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1554"
stix_relationship_id: "relationship--221a785c-45cc-42d7-9831-268a2d6019e3"
---
# Relationship 8537: G1048 — uses → T1554

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has trojanized Fortinet firmware and replaced the legitimate `/usr/bin/tac_plus` TACACS+ daemon for Linux with a malicious version containing credential logging functionality.(Citation: Google Cloud Mandiant UNC3886 2024)(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--221a785c-45cc-42d7-9831-268a2d6019e3`.
