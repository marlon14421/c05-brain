---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0063"
target_object: "S0099"
stix_relationship_id: "relationship--7231504b-153b-454a-a092-b5b2d01609e2"
---
# Relationship 8346: C0063 — uses → S0099

**Source object:** [[01 ATT&CK/C0063 - 2025 Poland Wiper Attacks|C0063: 2025 Poland Wiper Attacks]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0099 - Arp|S0099: Arp]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [2025 Poland Wiper Attacks](https://attack.mitre.org/campaigns/C0063), the adversaries used [Arp](https://attack.mitre.org/software/S0099) to write to a file named outlog.txt, including: currently running processes, network connections, routing tables, ARP cache, and the contents of user directories.(Citation: CERT Polska)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7231504b-153b-454a-a092-b5b2d01609e2`.
