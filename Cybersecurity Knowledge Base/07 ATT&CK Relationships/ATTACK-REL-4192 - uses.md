---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9042"
target_object: "T1569.003"
stix_relationship_id: "relationship--29d679e3-18bb-4cbc-bf1e-97f678be9cd3"
---
# Relationship 4192: S9042 — uses → T1569.003

**Source object:** [[01 ATT&CK/S9042 - CanisterWorm|S9042: CanisterWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.003 - Systemctl|T1569.003: Systemctl]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[CanisterWorm](https://attack.mitre.org/software/S9042) has used executed `systemctl --user daemon-reload` to reload systemd, then enables and starts the malicious service.(Citation: Aikido TeamPCP Trivy MAR 2026)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--29d679e3-18bb-4cbc-bf1e-97f678be9cd3`.
