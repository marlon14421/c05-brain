---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0049"
target_object: "T1594"
stix_relationship_id: "relationship--9d992708-bfc2-4c9c-95d2-d12b49985986"
---
# Relationship 4512: C0049 — uses → T1594

**Source object:** [[01 ATT&CK/C0049 - Leviathan Australian Intrusions|C0049: Leviathan Australian Intrusions]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1594 - Search Victim-Owned Websites|T1594: Search Victim-Owned Websites]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Leviathan](https://attack.mitre.org/groups/G0065) enumerated compromised web application resources to identify additional endpoints and resources linkd to the website for follow-on access during [Leviathan Australian Intrusions](https://attack.mitre.org/campaigns/C0049).(Citation: CISA Leviathan 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9d992708-bfc2-4c9c-95d2-d12b49985986`.
