---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1498"
stix_relationship_id: "relationship--5e9256c1-5ad5-4fb2-9a75-0267a2daae89"
---
# Relationship 3730: G0007 — uses → T1498

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1498 - Network Denial of Service|T1498: Network Denial of Service]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

In 2016, [APT28](https://attack.mitre.org/groups/G0007) conducted a distributed denial of service (DDoS) attack against the World Anti-Doping Agency.(Citation: US District Court Indictment GRU Oct 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5e9256c1-5ad5-4fb2-9a75-0267a2daae89`.
