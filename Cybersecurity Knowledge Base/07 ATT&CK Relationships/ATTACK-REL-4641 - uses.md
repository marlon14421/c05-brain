---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0131"
target_object: "T1090.002"
stix_relationship_id: "relationship--1dcca5db-e03e-4330-8705-76aaedcf295f"
---
# Relationship 4641: G0131 — uses → T1090.002

**Source object:** [[01 ATT&CK/G0131 - Tonto Team|G0131: Tonto Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090.002 - External Proxy|T1090.002: External Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Tonto Team](https://attack.mitre.org/groups/G0131) has routed their traffic through an external server in order to obfuscate their location.(Citation: TrendMicro Tonto Team October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1dcca5db-e03e-4330-8705-76aaedcf295f`.
