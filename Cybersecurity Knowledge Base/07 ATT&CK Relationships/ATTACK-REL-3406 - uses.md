---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0598"
target_object: "T1027"
stix_relationship_id: "relationship--8c73e0be-f105-4f22-93b4-cb765fb8f419"
---
# Relationship 3406: S0598 — uses → T1027

**Source object:** [[01 ATT&CK/S0598 - P.A.S. Webshell|S0598: P.A.S. Webshell]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[P.A.S. Webshell](https://attack.mitre.org/software/S0598) can use encryption and base64 encoding to hide strings and to enforce access control once deployed.(Citation: ANSSI Sandworm January 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8c73e0be-f105-4f22-93b4-cb765fb8f419`.
