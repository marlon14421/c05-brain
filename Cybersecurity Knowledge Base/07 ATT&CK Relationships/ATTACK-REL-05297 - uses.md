---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0259"
target_object: "T1059.003"
stix_relationship_id: "relationship--03a73f0c-218f-4ebf-81d2-88e2c8e9b883"
---
# Relationship 5297: S0259 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0259 - InnaputRAT|S0259: InnaputRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InnaputRAT](https://attack.mitre.org/software/S0259) launches a shell to execute commands on the victim’s machine.(Citation: ASERT InnaputRAT April 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03a73f0c-218f-4ebf-81d2-88e2c8e9b883`.
