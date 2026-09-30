---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0330"
target_object: "T1027.010"
stix_relationship_id: "relationship--bfbde4cb-a8e5-4e55-8700-7d25b17ecad1"
---
# Relationship 4994: S0330 — uses → T1027.010

**Source object:** [[01 ATT&CK/S0330 - Zeus Panda|S0330: Zeus Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Zeus Panda](https://attack.mitre.org/software/S0330) obfuscates the macro commands in its initial payload.(Citation: Talos Zeus Panda Nov 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfbde4cb-a8e5-4e55-8700-7d25b17ecad1`.
