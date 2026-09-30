---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0246"
target_object: "T1686.003"
stix_relationship_id: "relationship--c64da91b-77e2-4da8-9281-d363d490bd49"
---
# Relationship 2823: S0246 — uses → T1686.003

**Source object:** [[01 ATT&CK/S0246 - HARDRAIN|S0246: HARDRAIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1686.003 - Windows Host Firewall|T1686.003: Windows Host Firewall]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[HARDRAIN](https://attack.mitre.org/software/S0246) opens the Windows Firewall to modify incoming connections.(Citation: US-CERT HARDRAIN March 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c64da91b-77e2-4da8-9281-d363d490bd49`.
