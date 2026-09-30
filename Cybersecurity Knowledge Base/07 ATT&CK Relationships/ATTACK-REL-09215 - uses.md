---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1195.001"
stix_relationship_id: "relationship--d97f677b-85a4-4856-8aaa-92e35ade442a"
---
# Relationship 9215: S9042 — uses → T1195.001

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1195.001 - Compromise Software Dependencies and Development Tools|T1195.001: Compromise Software Dependencies and Development Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has spread through an automated process that infects and publishes npm packages.(Citation: Aikido TeamPCP Telnyx MAR 2026)(Citation: Aikido TeamPCP Trivy MAR 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d97f677b-85a4-4856-8aaa-92e35ade442a`.
