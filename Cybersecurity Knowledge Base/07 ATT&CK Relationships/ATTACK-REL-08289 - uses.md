---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0080"
target_object: "T1204.002"
stix_relationship_id: "relationship--5b078c2e-229d-4ef0-8e46-2164354caee9"
---
# Relationship 8289: G0080 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0080 - Cobalt Group|G0080: Cobalt Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Group](https://attack.mitre.org/groups/G0080) has sent emails containing malicious attachments that require users to execute a file or macro to infect the victim machine.(Citation: Talos Cobalt Group July 2018)(Citation: Unit 42 Cobalt Gang Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b078c2e-229d-4ef0-8e46-2164354caee9`.
