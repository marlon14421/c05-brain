---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0049"
target_object: "T1071.001"
stix_relationship_id: "relationship--b5a1cf65-c128-4d2e-bd28-54514d1a3aae"
---
# Relationship 3724: S0049 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0049 - GeminiDuke|S0049: GeminiDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[GeminiDuke](https://attack.mitre.org/software/S0049) uses HTTP and HTTPS for command and control.(Citation: F-Secure The Dukes)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5a1cf65-c128-4d2e-bd28-54514d1a3aae`.
