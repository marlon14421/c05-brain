---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0100"
target_object: "T1203"
stix_relationship_id: "relationship--b0702a30-f680-4f9b-99c3-352ce2a9557a"
---
# Relationship 5858: G0100 — uses → T1203

**Source object:** [[01 ATT&CK/G0100 - Inception|G0100: Inception]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Inception](https://attack.mitre.org/groups/G0100) has exploited CVE-2012-0158, CVE-2014-1761, CVE-2017-11882 and CVE-2018-0802 for execution.(Citation: Kaspersky Cloud Atlas August 2019)(Citation: Kaspersky Cloud Atlas December 2014)(Citation: Symantec Inception Framework March 2018)(Citation: Unit 42 Inception November 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b0702a30-f680-4f9b-99c3-352ce2a9557a`.
