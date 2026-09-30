---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1137.002"
stix_relationship_id: "relationship--d0560e25-020d-4cd6-b61c-5fc82a757edc"
---
# Relationship 9580: G0007 — uses → T1137.002

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1137.002 - Office Test|T1137.002: Office Test]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used the Office Test persistence mechanism within Microsoft Office by adding the Registry key HKCU\Software\Microsoft\Office test\Special\Perf to execute code.(Citation: Palo Alto Office Test Sofacy)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0560e25-020d-4cd6-b61c-5fc82a757edc`.
