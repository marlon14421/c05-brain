---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0035"
target_object: "T1685"
stix_relationship_id: "relationship--2963d541-8e6b-4376-a165-876145293a7e"
---
# Relationship 2922: C0035 — uses → T1685

**Source object:** [[01 ATT&CK/C0035 - KV Botnet Activity|C0035: KV Botnet Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[KV Botnet Activity](https://attack.mitre.org/campaigns/C0035) used various scripts to remove or disable security tools, such as http_watchdog and firewallsd , as well as tools related to other botnet infections, such as mips_ff , on victim devices.(Citation: Lumen KVBotnet 2023)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2963d541-8e6b-4376-a165-876145293a7e`.
