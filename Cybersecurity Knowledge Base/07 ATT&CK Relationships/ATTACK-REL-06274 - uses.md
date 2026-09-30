---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0373"
target_object: "T1059.003"
stix_relationship_id: "relationship--f1286eda-5b9a-4fd9-a506-bcc3b2870550"
---
# Relationship 6274: S0373 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0373 - Astaroth|S0373: Astaroth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Astaroth](https://attack.mitre.org/software/S0373) spawns a CMD process to execute commands. (Citation: Cybereason Astaroth Feb 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f1286eda-5b9a-4fd9-a506-bcc3b2870550`.
