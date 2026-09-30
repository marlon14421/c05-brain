---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1048"
target_object: "T1037"
stix_relationship_id: "relationship--ae7cff1e-cb46-45f5-8d96-e2448f64cfe2"
---
# Relationship 6140: G1048 — uses → T1037

**Source object:** [[01 ATT&CK/G1048 - UNC3886|G1048: UNC3886]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1037 - Boot or Logon Initialization Scripts|T1037: Boot or Logon Initialization Scripts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[UNC3886](https://attack.mitre.org/groups/G1048) has attempted to bypass digital signature verification checks at startup by adding a command to the startup config `/etc/init.d/localnet` within the rootfs.gz archive of both FortiManager and FortiAnalyzer devices.(Citation: Mandiant Fortinet Zero Day)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ae7cff1e-cb46-45f5-8d96-e2448f64cfe2`.
