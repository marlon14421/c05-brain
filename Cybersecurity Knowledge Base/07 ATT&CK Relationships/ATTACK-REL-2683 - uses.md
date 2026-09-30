---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0010"
target_object: "T1587.001"
stix_relationship_id: "relationship--a36264d2-5bb2-4268-8ce1-3de9fbdf2862"
---
# Relationship 2683: C0010 — uses → T1587.001

**Source object:** [[01 ATT&CK/C0010 - C0010|C0010: C0010]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For [C0010](https://attack.mitre.org/campaigns/C0010), UNC3890 actors used unique malware, including [SUGARUSH](https://attack.mitre.org/software/S1049) and [SUGARDUMP](https://attack.mitre.org/software/S1042).(Citation: Mandiant UNC3890 Aug 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a36264d2-5bb2-4268-8ce1-3de9fbdf2862`.
