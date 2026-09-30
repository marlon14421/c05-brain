---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0250"
target_object: "T1218.010"
stix_relationship_id: "relationship--2853aaaa-982e-49bf-a219-b4f16805b983"
---
# Relationship 2767: S0250 — uses → T1218.010

**Source object:** [[01 ATT&CK/S0250 - Koadic|S0250: Koadic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Koadic](https://attack.mitre.org/software/S0250) can use Regsvr32 to execute additional payloads.(Citation: Github Koadic)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2853aaaa-982e-49bf-a219-b4f16805b983`.
