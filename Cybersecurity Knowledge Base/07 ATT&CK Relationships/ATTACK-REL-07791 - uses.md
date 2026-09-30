---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1160"
target_object: "T1036.005"
stix_relationship_id: "relationship--8ac5b693-ed9b-483e-9f7c-7cd1357e3499"
---
# Relationship 7791: S1160 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1160 - Latrodectus|S1160: Latrodectus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Latrodectus](https://attack.mitre.org/software/S1160) has been packed to appear as a component to Bitdefender’s kernel-mode driver, TRUFOS.SYS.(Citation: Elastic Latrodectus May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8ac5b693-ed9b-483e-9f7c-7cd1357e3499`.
