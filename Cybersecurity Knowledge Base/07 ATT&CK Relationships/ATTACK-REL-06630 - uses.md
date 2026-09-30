---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1045"
target_object: "T1110.002"
stix_relationship_id: "relationship--873d3695-4cd9-4e82-93d6-3960ae1efd4a"
---
# Relationship 6630: G1045 — uses → T1110.002

**Source object:** [[01 ATT&CK/G1045 - Salt Typhoon|G1045: Salt Typhoon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1110.002 - Password Cracking|T1110.002: Password Cracking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Salt Typhoon](https://attack.mitre.org/groups/G1045) has cracked passwords for accounts with weak encryption obtained from the configuration files of compromised network devices.(Citation: Cisco Salt Typhoon FEB 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--873d3695-4cd9-4e82-93d6-3960ae1efd4a`.
