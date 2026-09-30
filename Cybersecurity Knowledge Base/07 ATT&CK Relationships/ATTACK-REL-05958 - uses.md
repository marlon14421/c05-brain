---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1201"
target_object: "T1539"
stix_relationship_id: "relationship--8af30aa3-c5b7-4273-9de4-98fe5b2f4bf5"
---
# Relationship 5958: S1201 — uses → T1539

**Source object:** [[01 ATT&CK/S1201 - TRANSLATEXT|S1201: TRANSLATEXT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1539 - Steal Web Session Cookie|T1539: Steal Web Session Cookie]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TRANSLATEXT](https://attack.mitre.org/software/S1201) has exfiltrated updated cookies from Google, Naver, Kakao or Daum to the C2 server.(Citation: Zscaler Kimsuky TRANSLATEXT)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8af30aa3-c5b7-4273-9de4-98fe5b2f4bf5`.
