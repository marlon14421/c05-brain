---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1210"
stix_relationship_id: "relationship--14f3eebf-40c3-48d5-ad62-356d57ccf2dc"
---
# Relationship 8976: G0102 — uses → T1210

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has exploited or attempted to exploit Zerologon (CVE-2020-1472) and EternalBlue (MS17-010) vulnerabilities.(Citation: FireEye KEGTAP SINGLEMALT October 2020)(Citation: DFIR Ryuk's Return October 2020)(Citation: DFIR Ryuk in 5 Hours October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--14f3eebf-40c3-48d5-ad62-356d57ccf2dc`.
