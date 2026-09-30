---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1031"
target_object: "T1221"
stix_relationship_id: "relationship--a24399b5-218e-41b5-8904-9e8e0599ae25"
---
# Relationship 0120: M1031 — mitigates → T1221

**Source object:** [[01 ATT&CK/M1031 - Network Intrusion Prevention|M1031: Network Intrusion Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1221 - Template Injection|T1221: Template Injection]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Network/Host intrusion prevention systems, antivirus, and detonation chambers can be employed to prevent documents from fetching and/or executing malicious payloads.(Citation: Anomali Template Injection MAR 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a24399b5-218e-41b5-8904-9e8e0599ae25`.
