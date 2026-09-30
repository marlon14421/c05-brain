---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0070"
target_object: "T1105"
stix_relationship_id: "relationship--0e12d7d1-5c46-4314-97fb-263853eed6af"
---
# Relationship 4637: S0070 — uses → T1105

**Source object:** [[01 ATT&CK/S0070 - HTTPBrowser|S0070: HTTPBrowser]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HTTPBrowser](https://attack.mitre.org/software/S0070) is capable of writing a file to the compromised system from the C2 server.(Citation: Dell TG-3390)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0e12d7d1-5c46-4314-97fb-263853eed6af`.
