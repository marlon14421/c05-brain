---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0501"
target_object: "T1547.012"
stix_relationship_id: "relationship--74bc9883-6d48-4e68-bc61-1fea450e89e7"
---
# Relationship 2962: S0501 — uses → T1547.012

**Source object:** [[01 ATT&CK/S0501 - PipeMon|S0501: PipeMon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.012 - Print Processors|T1547.012: Print Processors]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

The [PipeMon](https://attack.mitre.org/software/S0501) installer has modified the Registry key HKLM\SYSTEM\CurrentControlSet\Control\Print\Environments\Windows x64\Print Processors to install [PipeMon](https://attack.mitre.org/software/S0501) as a Print Processor.(Citation: ESET PipeMon May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74bc9883-6d48-4e68-bc61-1fea450e89e7`.
