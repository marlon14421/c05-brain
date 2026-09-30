---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0085"
target_object: "T1547.009"
stix_relationship_id: "relationship--907df22e-fdfe-4b93-8b18-ebf66f83868c"
---
# Relationship 4452: S0085 — uses → T1547.009

**Source object:** [[01 ATT&CK/S0085 - S-Type|S0085: S-Type]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.009 - Shortcut Modification|T1547.009: Shortcut Modification]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[S-Type](https://attack.mitre.org/software/S0085) may create the file %HOMEPATH%\Start Menu\Programs\Startup\Realtek {Unique Identifier}.lnk , which points to the malicious `msdtc.exe` file already created in the `%CommonFiles%` directory.(Citation: Cylance Dust Storm)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--907df22e-fdfe-4b93-8b18-ebf66f83868c`.
