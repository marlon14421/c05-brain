---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1608.001"
stix_relationship_id: "relationship--1ff37097-9ec1-42cd-bdd6-52d74ab8e3b5"
---
# Relationship 6189: G0094 — uses → T1608.001

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.001 - Upload Malware|T1608.001: Upload Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used compromised and acquired infrastructure to host and deliver malware including Blogspot to host beacons, file exfiltrators, and implants.(Citation: Talos Kimsuky Nov 2021)(Citation: Mandiant APT43 March 2024) [Kimsuky](https://attack.mitre.org/groups/G0094) has also hosted malicious payloads on Dropbox.(Citation: Securonix Kimsuky February 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ff37097-9ec1-42cd-bdd6-52d74ab8e3b5`.
