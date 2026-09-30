---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1614.001"
stix_relationship_id: "relationship--faccdb82-54fb-4d6c-a2ec-7cbfc9e5cc13"
---
# Relationship 4035: S9042 — uses → T1614.001

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has checked the target system's timezone `(/etc/timezone, timedatectl)` for `Asia/Tehran` or `Iran` and the `LANG` environment variable for `fa_IR` to identify systems matching an Iranian locale prior to deploying its destructive wiper component.(Citation: Palo Alto TeamPCP MAR 2026)(Citation: Aikido CanisterWorm MAR 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--faccdb82-54fb-4d6c-a2ec-7cbfc9e5cc13`.
