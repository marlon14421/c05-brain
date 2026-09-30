---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0189"
target_object: "T1027"
stix_relationship_id: "relationship--a0500766-a6ba-4672-b7fc-2a712cd0cfca"
---
# Relationship 3629: S0189 — uses → T1027

**Source object:** [[01 ATT&CK/S0189 - ISMInjector|S0189: ISMInjector]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ISMInjector](https://attack.mitre.org/software/S0189) is obfuscated with the off-the-shelf SmartAssembly .NET obfuscator created by red-gate.com.(Citation: OilRig New Delivery Oct 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a0500766-a6ba-4672-b7fc-2a712cd0cfca`.
