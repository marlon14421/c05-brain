---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0278"
target_object: "T1560.001"
stix_relationship_id: "relationship--90bd9900-a78f-47da-9504-393e8ece3fac"
---
# Relationship 5252: S0278 — uses → T1560.001

**Source object:** [[01 ATT&CK/S0278 - iKitten|S0278: iKitten]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[iKitten](https://attack.mitre.org/software/S0278) will zip up the /Library/Keychains directory before exfiltrating it.(Citation: objsee mac malware 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--90bd9900-a78f-47da-9504-393e8ece3fac`.
