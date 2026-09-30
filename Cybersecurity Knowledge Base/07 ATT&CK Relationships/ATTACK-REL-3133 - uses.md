---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1164"
target_object: "T1001.001"
stix_relationship_id: "relationship--a3dba415-6593-445b-8294-503b53c59109"
---
# Relationship 3133: S1164 — uses → T1001.001

**Source object:** [[01 ATT&CK/S1164 - UPSTYLE|S1164: UPSTYLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1001.001 - Junk Data|T1001.001: Junk Data]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[UPSTYLE](https://attack.mitre.org/software/S1164) retrieves a non-existent webpage from the command and control server then parses commands from the resulting error logs to decode commands to the web shell.(Citation: Volexity UPSTYLE 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3dba415-6593-445b-8294-503b53c59109`.
