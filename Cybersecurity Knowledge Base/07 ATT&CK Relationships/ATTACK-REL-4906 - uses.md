---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0351"
target_object: "T1041"
stix_relationship_id: "relationship--48106cb0-a9c8-4c68-b90a-8d517078d189"
---
# Relationship 4906: S0351 — uses → T1041

**Source object:** [[01 ATT&CK/S0351 - Cannon|S0351: Cannon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cannon](https://attack.mitre.org/software/S0351) exfiltrates collected data over email via SMTP/S and POP3/S C2 channels.(Citation: Unit42 Cannon Nov 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--48106cb0-a9c8-4c68-b90a-8d517078d189`.
