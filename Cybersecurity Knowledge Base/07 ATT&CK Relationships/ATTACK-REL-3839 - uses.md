---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0211"
target_object: "T1070.004"
stix_relationship_id: "relationship--62eee3f5-f7ab-4029-a690-635452f1def7"
---
# Relationship 3839: S0211 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0211 - Linfo|S0211: Linfo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Linfo](https://attack.mitre.org/software/S0211) creates a backdoor through which remote attackers can delete files.(Citation: Symantec Linfo May 2012)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--62eee3f5-f7ab-4029-a690-635452f1def7`.
