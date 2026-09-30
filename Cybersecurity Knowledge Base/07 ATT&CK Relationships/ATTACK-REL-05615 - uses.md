---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0030"
target_object: "T1587.001"
stix_relationship_id: "relationship--97ca11ce-025d-4e46-93d7-deadd4bcd780"
---
# Relationship 5615: C0030 — uses → T1587.001

**Source object:** [[01 ATT&CK/C0030 - Triton Safety Instrumented System Attack|C0030: Triton Safety Instrumented System Attack]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

In the [Triton Safety Instrumented System Attack](https://attack.mitre.org/campaigns/C0030), [TEMP.Veles](https://attack.mitre.org/groups/G0088) developed, prior to the attack, malware capabilities that would require access to specific and specialized hardware and software.(Citation: FireEye TRITON Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97ca11ce-025d-4e46-93d7-deadd4bcd780`.
