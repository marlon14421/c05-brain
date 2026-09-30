---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0629"
target_object: "T1005"
stix_relationship_id: "relationship--ecbe6cc7-16cc-474f-91fe-bd3e9014abbf"
---
# Relationship 4057: S0629 — uses → T1005

**Source object:** [[01 ATT&CK/S0629 - RainyDay|S0629: RainyDay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[RainyDay](https://attack.mitre.org/software/S0629) can use a file exfiltration tool to collect recently changed files on a compromised host.(Citation: Bitdefender Naikon April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ecbe6cc7-16cc-474f-91fe-bd3e9014abbf`.
