---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0143"
target_object: "T1595.002"
stix_relationship_id: "relationship--bcd8dfe5-6f81-406c-a06a-7aa83db91a5e"
---
# Relationship 9409: G0143 — uses → T1595.002

**Source object:** [[01 ATT&CK/G0143 - Aquatic Panda|G0143: Aquatic Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1595.002 - Vulnerability Scanning|T1595.002: Vulnerability Scanning]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Aquatic Panda](https://attack.mitre.org/groups/G0143) has used publicly accessible DNS logging services to identify servers vulnerable to Log4j (CVE 2021-44228).(Citation: CrowdStrike AQUATIC PANDA December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bcd8dfe5-6f81-406c-a06a-7aa83db91a5e`.
