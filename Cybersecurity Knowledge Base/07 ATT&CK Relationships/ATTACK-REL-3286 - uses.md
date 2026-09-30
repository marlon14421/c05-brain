---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9028"
target_object: "T1505.003"
stix_relationship_id: "relationship--12f2d741-15cd-43b0-9c05-06f8295ab547"
---
# Relationship 3286: S9028 — uses → T1505.003

**Source object:** [[01 ATT&CK/S9028 - PHPsert|S9028: PHPsert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1505.003 - Web Shell|T1505.003: Web Shell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PHPsert](https://attack.mitre.org/software/S9028) can use the .php assert function to execute attacker-provided code and maintain persistence on targeted web servers.(Citation: sentinelone operationDigitalEye Dec 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--12f2d741-15cd-43b0-9c05-06f8295ab547`.
