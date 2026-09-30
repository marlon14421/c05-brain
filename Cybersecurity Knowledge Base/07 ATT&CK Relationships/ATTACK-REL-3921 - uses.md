---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0015"
target_object: "T1564.001"
stix_relationship_id: "relationship--7fd0dc68-66b1-482a-b3bd-3037bb0045cb"
---
# Relationship 3921: S0015 — uses → T1564.001

**Source object:** [[01 ATT&CK/S0015 - Ixeshe|S0015: Ixeshe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ixeshe](https://attack.mitre.org/software/S0015) sets its own executable file's attributes to hidden.(Citation: Trend Micro IXESHE 2012)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7fd0dc68-66b1-482a-b3bd-3037bb0045cb`.
