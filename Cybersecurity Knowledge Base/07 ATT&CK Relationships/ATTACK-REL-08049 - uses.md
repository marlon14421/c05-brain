---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0128"
target_object: "T1036"
stix_relationship_id: "relationship--a3990ec1-b4bb-43dd-b7d8-51bd3cb7e1c7"
---
# Relationship 8049: G0128 — uses → T1036

**Source object:** [[01 ATT&CK/G0128 - ZIRCONIUM|G0128: ZIRCONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has spoofed legitimate applications in phishing lures and changed file extensions to conceal installation of malware.(Citation: Google Election Threats October 2020)(Citation: Zscaler APT31 Covid-19 October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3990ec1-b4bb-43dd-b7d8-51bd3cb7e1c7`.
