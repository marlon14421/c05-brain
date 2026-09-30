---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0487"
target_object: "T1132.001"
stix_relationship_id: "relationship--90126438-03a9-47c8-98c1-222a1d79ef21"
---
# Relationship 3802: S0487 — uses → T1132.001

**Source object:** [[01 ATT&CK/S0487 - Kessel|S0487: Kessel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1132.001 - Standard Encoding|T1132.001: Standard Encoding]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kessel](https://attack.mitre.org/software/S0487) has exfiltrated data via hexadecimal-encoded subdomain fields of DNS queries.(Citation: ESET ForSSHe December 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90126438-03a9-47c8-98c1-222a1d79ef21`.
