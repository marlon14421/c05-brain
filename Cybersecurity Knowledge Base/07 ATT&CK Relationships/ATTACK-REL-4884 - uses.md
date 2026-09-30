---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0486"
target_object: "T1554"
stix_relationship_id: "relationship--bc40c6be-575a-4eb9-981f-fa6c127d2286"
---
# Relationship 4884: S0486 — uses → T1554

**Source object:** [[01 ATT&CK/S0486 - Bonadan|S0486: Bonadan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Bonadan](https://attack.mitre.org/software/S0486) has maliciously altered the OpenSSH binary on targeted systems to create a backdoor.(Citation: ESET ForSSHe December 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bc40c6be-575a-4eb9-981f-fa6c127d2286`.
