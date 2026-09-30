---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0148"
target_object: "T1568"
stix_relationship_id: "relationship--25eb9cd3-80e1-4116-bfd3-fa3819dc2079"
---
# Relationship 5963: S0148 — uses → T1568

**Source object:** [[01 ATT&CK/S0148 - RTM|S0148: RTM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1568 - Dynamic Resolution|T1568: Dynamic Resolution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RTM](https://attack.mitre.org/software/S0148) has resolved [Pony](https://attack.mitre.org/software/S0453) C2 server IP addresses by either converting Bitcoin blockchain transaction data to specific octets, or accessing IP addresses directly within the Namecoin blockchain.(Citation: CheckPoint Redaman October 2019)(Citation: Unit42 Redaman January 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25eb9cd3-80e1-4116-bfd3-fa3819dc2079`.
