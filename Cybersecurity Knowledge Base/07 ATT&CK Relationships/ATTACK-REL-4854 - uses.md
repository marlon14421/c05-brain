---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1203"
stix_relationship_id: "relationship--74316a28-d1a6-40b8-8c49-836f06e90e02"
---
# Relationship 4854: G0040 — uses → T1203

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1203 - Exploitation for Client Execution|T1203: Exploitation for Client Execution]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) uses malicious documents to deliver remote execution exploits as part of. The group has previously exploited CVE-2017-8570, CVE-2012-1856, CVE-2014-4114, CVE-2017-0199, CVE-2017-11882, and CVE-2015-1641.(Citation: Cymmetria Patchwork)(Citation: Securelist Dropping Elephant)(Citation: Symantec Patchwork)(Citation: PaloAlto Patchwork Mar 2018)(Citation: TrendMicro Patchwork Dec 2017)(Citation: Volexity Patchwork June 2018)(Citation: Unit 42 BackConfig May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74316a28-d1a6-40b8-8c49-836f06e90e02`.
