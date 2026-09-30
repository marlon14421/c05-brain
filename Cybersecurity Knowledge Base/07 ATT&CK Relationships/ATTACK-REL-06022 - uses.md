---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0082"
target_object: "T1059.003"
stix_relationship_id: "relationship--3ab4c52a-aa3d-4c65-bd68-6614a0fb7bfe"
---
# Relationship 6022: G0082 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0082 - APT38|G0082: APT38]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT38](https://attack.mitre.org/groups/G0082) has used a command-line tunneler, NACHOCHEESE, to give them shell access to a victim’s machine.(Citation: FireEye APT38 Oct 2018) Additionally, [APT38](https://attack.mitre.org/groups/G0082) has used batch scripts.(Citation: 1 - appv)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ab4c52a-aa3d-4c65-bd68-6614a0fb7bfe`.
