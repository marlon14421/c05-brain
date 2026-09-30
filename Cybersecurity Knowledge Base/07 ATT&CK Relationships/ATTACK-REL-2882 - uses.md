---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0204"
target_object: "T1218.011"
stix_relationship_id: "relationship--138da0bb-befa-45cd-9ca4-c74b86ac61ff"
---
# Relationship 2882: S0204 — uses → T1218.011

**Source object:** [[01 ATT&CK/S0204 - Briba|S0204: Briba]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.011 - Rundll32|T1218.011: Rundll32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Briba](https://attack.mitre.org/software/S0204) uses rundll32 within [Registry Run Keys / Startup Folder](https://attack.mitre.org/techniques/T1547/001) entries to execute malicious DLLs.(Citation: Symantec Briba May 2012)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--138da0bb-befa-45cd-9ca4-c74b86ac61ff`.
