---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1041"
stix_relationship_id: "relationship--a9bb532c-48bf-4103-8e9f-a8951e6c0882"
---
# Relationship 2929: S9008 — uses → T1041

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has used POST to exfiltrate secrets from the victim environment to an attacker-controlled URL.(Citation: Aikido Shai-Hulud September 2025)(Citation: Palo Alto Unit 42 Shai-Hulud November 2025)(Citation: Wiz Shai-Hulud September 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a9bb532c-48bf-4103-8e9f-a8951e6c0882`.
