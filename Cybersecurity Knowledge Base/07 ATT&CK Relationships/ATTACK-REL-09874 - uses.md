---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1213"
target_object: "T1176.001"
stix_relationship_id: "relationship--8b05c779-8401-4c2f-a652-dc1ff91f34cd"
---
# Relationship 9874: S1213 — uses → T1176.001

**Source object:** [[01 ATT&CK/S1213 - Lumma Stealer|S1213: Lumma Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1176.001 - Browser Extensions|T1176.001: Browser Extensions]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lumma Stealer](https://attack.mitre.org/software/S1213) has installed a malicious browser extension to target Google Chrome, Microsoft Edge, Opera and Brave browsers for the purpose of stealing data.(Citation: Cybereason LumaStealer Undated)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b05c779-8401-4c2f-a652-dc1ff91f34cd`.
