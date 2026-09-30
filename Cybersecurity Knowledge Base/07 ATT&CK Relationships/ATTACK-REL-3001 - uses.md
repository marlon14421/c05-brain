---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0663"
target_object: "T1105"
stix_relationship_id: "relationship--759ce6e8-da01-4cd6-9d03-9b0a1edde9be"
---
# Relationship 3001: S0663 — uses → T1105

**Source object:** [[01 ATT&CK/S0663 - SysUpdate|S0663: SysUpdate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SysUpdate](https://attack.mitre.org/software/S0663) has the ability to download files to a compromised host.(Citation: Trend Micro Iron Tiger April 2021)(Citation: Lunghi Iron Tiger Linux)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--759ce6e8-da01-4cd6-9d03-9b0a1edde9be`.
