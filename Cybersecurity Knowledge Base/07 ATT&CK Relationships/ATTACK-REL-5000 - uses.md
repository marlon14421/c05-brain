---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0037"
target_object: "T1087.002"
stix_relationship_id: "relationship--16c7058c-8fa5-4477-8332-9e76fcb38924"
---
# Relationship 5000: G0037 — uses → T1087.002

**Source object:** [[01 ATT&CK/G0037 - FIN6|G0037: FIN6]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1087.002 - Domain Account|T1087.002: Domain Account]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN6](https://attack.mitre.org/groups/G0037) has used Metasploit’s [PsExec](https://attack.mitre.org/software/S0029) NTDSGRAB module to obtain a copy of the victim's Active Directory database.(Citation: FireEye FIN6 April 2016)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16c7058c-8fa5-4477-8332-9e76fcb38924`.
