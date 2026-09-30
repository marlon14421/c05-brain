---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1053"
target_object: "T1588.006"
stix_relationship_id: "relationship--ec384765-a84b-40f3-abf9-5bec1f7e5f10"
---
# Relationship 8275: G1053 — uses → T1588.006

**Source object:** [[01 ATT&CK/G1053 - Storm-0501|G1053: Storm-0501]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.006 - Vulnerabilities|T1588.006: Vulnerabilities]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Storm-0501](https://attack.mitre.org/groups/G1053) has obtained capabilities to exploit N-day vulnerabilities associated with public facing services to gain initial access to victim environments to include Zoho ManageEngine (CVE-2022-47966), Citrix NetScaler “Citrix Bleed” (CVE-2023-4966), and Adobe ColdFusion 2016 (CVE-2023-29300 or CVE-2023-38203).(Citation: Microsoft Storm-501 Sabbath Ransomware Embargo September 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec384765-a84b-40f3-abf9-5bec1f7e5f10`.
