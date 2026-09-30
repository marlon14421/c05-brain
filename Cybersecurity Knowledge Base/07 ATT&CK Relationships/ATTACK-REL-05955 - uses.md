---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0401"
target_object: "T1543"
stix_relationship_id: "relationship--5a832b2f-7aa5-4a11-a06a-5cd22fb7f457"
---
# Relationship 5955: S0401 — uses → T1543

**Source object:** [[01 ATT&CK/S0401 - Exaramel for Linux|S0401: Exaramel for Linux]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543 - Create or Modify System Process|T1543: Create or Modify System Process]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Exaramel for Linux](https://attack.mitre.org/software/S0401) has a hardcoded location that it uses to achieve persistence if the startup system is Upstart or System V and it is running as root.(Citation: ANSSI Sandworm January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a832b2f-7aa5-4a11-a06a-5cd22fb7f457`.
