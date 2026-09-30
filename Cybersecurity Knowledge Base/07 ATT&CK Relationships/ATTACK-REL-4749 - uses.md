---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0022"
target_object: "T1095"
stix_relationship_id: "relationship--3717f0c2-0963-4b6c-9603-bb01c06b9fe6"
---
# Relationship 4749: S0022 — uses → T1095

**Source object:** [[01 ATT&CK/S0022 - Uroburos|S0022: Uroburos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Uroburos](https://attack.mitre.org/software/S0022) can communicate through custom methodologies for UDP, ICMP, and TCP that use distinct sessions to ride over the legitimate protocols.(Citation: Joint Cybersecurity Advisory AA23-129A Snake Malware May 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3717f0c2-0963-4b6c-9603-bb01c06b9fe6`.
