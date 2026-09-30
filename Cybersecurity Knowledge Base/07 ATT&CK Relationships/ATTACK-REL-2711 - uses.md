---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0094"
target_object: "T1055.003"
stix_relationship_id: "relationship--8e34d10d-0c24-41c6-8bde-727768256479"
---
# Relationship 2711: S0094 — uses → T1055.003

**Source object:** [[01 ATT&CK/S0094 - Trojan.Karagany|S0094: Trojan.Karagany]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.003 - Thread Execution Hijacking|T1055.003: Thread Execution Hijacking]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Trojan.Karagany](https://attack.mitre.org/software/S0094) can inject a suspended thread of its own process into a new process and initiate via the ResumeThread API.(Citation: Secureworks Karagany July 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8e34d10d-0c24-41c6-8bde-727768256479`.
