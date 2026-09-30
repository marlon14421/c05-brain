---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1552.004"
stix_relationship_id: "relationship--54e92c5b-28d0-4506-8d8c-bb582d8b7172"
---
# Relationship 5931: G0094 — uses → T1552.004

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.004 - Private Keys|T1552.004: Private Keys]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has accessed a Local State files associated with Chromium-based browsers that contain the AES key used to encrypt passwords stored in the browser to include `app_bound_encrypted_key`.(Citation: Aryaka Kimsuky July 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--54e92c5b-28d0-4506-8d8c-bb582d8b7172`.
