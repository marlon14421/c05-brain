---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1155"
target_object: "T1059.003"
stix_relationship_id: "relationship--6e4ba4ea-69c2-4e44-a69b-1f128dc1dcfe"
---
# Relationship 5676: S1155 — uses → T1059.003

**Source object:** [[01 ATT&CK/S1155 - Covenant|S1155: Covenant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Covenant](https://attack.mitre.org/software/S1155) provides access to a Command Shell in Windows environments for follow-on command execution and tasking.(Citation: Github Covenant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e4ba4ea-69c2-4e44-a69b-1f128dc1dcfe`.
