---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "T1001"
stix_relationship_id: "relationship--80a8cd03-8f65-41fb-803a-64d92f9f1522"
---
# Relationship 3297: C0014 — uses → T1001

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001 - Data Obfuscation|T1001: Data Obfuscation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Wocao](https://attack.mitre.org/campaigns/C0014), threat actors encrypted IP addresses used for "Agent" proxy hops with RC4.(Citation: FoxIT Wocao December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--80a8cd03-8f65-41fb-803a-64d92f9f1522`.
