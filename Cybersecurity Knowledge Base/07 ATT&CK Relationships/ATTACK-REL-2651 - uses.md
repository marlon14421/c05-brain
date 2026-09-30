---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0528"
target_object: "T1105"
stix_relationship_id: "relationship--fe518957-8722-498f-8da0-4b5eca466cef"
---
# Relationship 2651: S0528 — uses → T1105

**Source object:** [[01 ATT&CK/S0528 - Javali|S0528: Javali]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Javali](https://attack.mitre.org/software/S0528) can download payloads from remote C2 servers.(Citation: Securelist Brazilian Banking Malware July 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe518957-8722-498f-8da0-4b5eca466cef`.
