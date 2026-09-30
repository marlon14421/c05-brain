---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0096"
target_object: "T1105"
stix_relationship_id: "relationship--b42c23c9-99f4-4b1f-91e2-a945a119fe98"
---
# Relationship 7410: G0096 — uses → T1105

**Source object:** [[01 ATT&CK/G0096 - APT41|G0096: APT41]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT41](https://attack.mitre.org/groups/G0096) used [certutil](https://attack.mitre.org/software/S0160) to download additional files.(Citation: FireEye APT41 March 2020)(Citation: Crowdstrike GTR2020 Mar 2020)(Citation: Group IB APT 41 June 2021) [APT41](https://attack.mitre.org/groups/G0096) downloaded post-exploitation tools such as [Cobalt Strike](https://attack.mitre.org/software/S0154) via command shell following initial access.(Citation: Rostovcev APT41 2021) [APT41](https://attack.mitre.org/groups/G0096) has uploaded Procdump and NATBypass to a staging directory and has used these tools in follow-on activities.(Citation: apt41_dcsocytec_dec2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b42c23c9-99f4-4b1f-91e2-a945a119fe98`.
