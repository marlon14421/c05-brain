---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0263"
target_object: "T1090"
stix_relationship_id: "relationship--83e001e3-95d3-43d9-9f8c-8b954686287a"
---
# Relationship 4216: S0263 — uses → T1090

**Source object:** [[01 ATT&CK/S0263 - TYPEFRAME|S0263: TYPEFRAME]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

A [TYPEFRAME](https://attack.mitre.org/software/S0263) variant can force the compromised system to function as a proxy server.(Citation: US-CERT TYPEFRAME June 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83e001e3-95d3-43d9-9f8c-8b954686287a`.
