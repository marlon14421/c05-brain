---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0487"
target_object: "T1030"
stix_relationship_id: "relationship--45852cf6-f0e8-45b8-9636-0dee90f7d2fc"
---
# Relationship 3344: S0487 — uses → T1030

**Source object:** [[01 ATT&CK/S0487 - Kessel|S0487: Kessel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1030 - Data Transfer Size Limits|T1030: Data Transfer Size Limits]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kessel](https://attack.mitre.org/software/S0487) can split the data to be exilftrated into chunks that will fit in subdomains of DNS queries.(Citation: ESET ForSSHe December 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--45852cf6-f0e8-45b8-9636-0dee90f7d2fc`.
