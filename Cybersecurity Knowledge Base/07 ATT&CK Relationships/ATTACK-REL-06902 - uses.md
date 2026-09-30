---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1203"
target_object: "T1040"
stix_relationship_id: "relationship--d5cd9334-11f1-42c8-b332-8a0aa884e254"
---
# Relationship 6902: S1203 — uses → T1040

**Source object:** [[01 ATT&CK/S1203 - J-magic|S1203: J-magic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1040 - Network Sniffing|T1040: Network Sniffing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[J-magic](https://attack.mitre.org/software/S1203) has a pcap listener function that can create an Extended Berkley Packet Filter (eBPF) on designated interfaces and ports.(Citation: Lumen J-Magic JAN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d5cd9334-11f1-42c8-b332-8a0aa884e254`.
