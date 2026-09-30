---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9031"
target_object: "T1574.001"
stix_relationship_id: "relationship--4ac9f066-58e8-4e8d-bfaa-12520294885c"
---
# Relationship 7553: S9031 — uses → T1574.001

**Source object:** [[01 ATT&CK/S9031 - AshTag|S9031: AshTag]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[AshTag](https://attack.mitre.org/software/S9031) has enabled execution via DLL sideloading using a legitimate executable paired with a malicious DLL named wtsapi32.(Citation: Palo Alto Ashen Lepus DEC 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4ac9f066-58e8-4e8d-bfaa-12520294885c`.
