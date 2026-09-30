---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1110"
target_object: "T1074.001"
stix_relationship_id: "relationship--0f578b99-3d14-4416-8936-51e11d71a47b"
---
# Relationship 3805: S1110 — uses → T1074.001

**Source object:** [[01 ATT&CK/S1110 - SLIGHTPULSE|S1110: SLIGHTPULSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SLIGHTPULSE](https://attack.mitre.org/software/S1110) has piped the output from executed commands to `/tmp/1`.(Citation: Mandiant Pulse Secure Zero-Day April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0f578b99-3d14-4416-8936-51e11d71a47b`.
