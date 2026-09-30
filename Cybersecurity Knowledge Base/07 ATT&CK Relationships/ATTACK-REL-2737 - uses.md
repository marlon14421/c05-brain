---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1587.002"
stix_relationship_id: "relationship--9319fb2f-88df-4195-a42e-2a6a983a4840"
---
# Relationship 2737: G0040 — uses → T1587.002

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.002 - Code Signing Certificates|T1587.002: Code Signing Certificates]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) has created self-signed certificates from fictitious and spoofed legitimate software companies that were later used to sign malware.(Citation: Unit 42 BackConfig May 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9319fb2f-88df-4195-a42e-2a6a983a4840`.
