---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1211"
stix_relationship_id: "relationship--e5706e1a-33a9-4404-9ef8-c8aa428363ec"
---
# Relationship 6111: G0007 — uses → T1211

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1211 - Exploitation for Stealth|T1211: Exploitation for Stealth]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) has used CVE-2015-4902 to bypass security features.(Citation: Bitdefender APT28 Dec 2015)(Citation: Microsoft SIR Vol 19)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e5706e1a-33a9-4404-9ef8-c8aa428363ec`.
