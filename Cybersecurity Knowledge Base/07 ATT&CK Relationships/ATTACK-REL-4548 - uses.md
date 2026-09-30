---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0499"
target_object: "T1566.002"
stix_relationship_id: "relationship--c1b55dea-5e5d-4cff-bfac-5880507389c1"
---
# Relationship 4548: S0499 — uses → T1566.002

**Source object:** [[01 ATT&CK/S0499 - Hancitor|S0499: Hancitor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.002 - Spearphishing Link|T1566.002: Spearphishing Link]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Hancitor](https://attack.mitre.org/software/S0499) has been delivered via phishing emails which contained malicious links.(Citation: Threatpost Hancitor)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1b55dea-5e5d-4cff-bfac-5880507389c1`.
