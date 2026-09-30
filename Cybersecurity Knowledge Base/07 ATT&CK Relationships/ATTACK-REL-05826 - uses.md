---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "T1070.004"
stix_relationship_id: "relationship--32621114-725a-4766-b057-2d091adba75b"
---
# Relationship 5826: C0029 — uses → T1070.004

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Cutting Edge](https://attack.mitre.org/campaigns/C0029), threat actors deleted `/tmp/test1.txt` on compromised Ivanti Connect Secure VPNs which was used to hold stolen configuration and cache files.(Citation: Mandiant Cutting Edge Part 2 January 2024)(Citation: Mandiant Cutting Edge Part 3 February 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--32621114-725a-4766-b057-2d091adba75b`.
