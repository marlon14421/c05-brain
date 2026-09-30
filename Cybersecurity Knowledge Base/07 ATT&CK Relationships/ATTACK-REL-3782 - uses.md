---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0412"
target_object: "T1090"
stix_relationship_id: "relationship--2bd05bbf-886e-4211-8aab-63cd8581a695"
---
# Relationship 3782: S0412 — uses → T1090

**Source object:** [[01 ATT&CK/S0412 - ZxShell|S0412: ZxShell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZxShell](https://attack.mitre.org/software/S0412) can set up an HTTP or SOCKS proxy.(Citation: FireEye APT41 Aug 2019)(Citation: Talos ZxShell Oct 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2bd05bbf-886e-4211-8aab-63cd8581a695`.
