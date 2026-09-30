---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0171"
target_object: "T1082"
stix_relationship_id: "relationship--9f653750-2ee6-4d00-906b-c71f1d217288"
---
# Relationship 3298: S0171 — uses → T1082

**Source object:** [[01 ATT&CK/S0171 - Felismus|S0171: Felismus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Felismus](https://attack.mitre.org/software/S0171) collects the system information, including hostname and OS version, and sends it to the C2 server.(Citation: Forcepoint Felismus Mar 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f653750-2ee6-4d00-906b-c71f1d217288`.
