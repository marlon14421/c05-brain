---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0623"
target_object: "T1611"
stix_relationship_id: "relationship--6c91f220-34c0-4d9a-8e23-e1a4b29742dc"
---
# Relationship 5838: S0623 — uses → T1611

**Source object:** [[01 ATT&CK/S0623 - Siloscape|S0623: Siloscape]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1611 - Escape to Host|T1611: Escape to Host]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Siloscape](https://attack.mitre.org/software/S0623) maps the host’s C drive to the container by creating a global symbolic link to the host through the calling of NtSetInformationSymbolicLink .(Citation: Unit 42 Siloscape Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6c91f220-34c0-4d9a-8e23-e1a4b29742dc`.
