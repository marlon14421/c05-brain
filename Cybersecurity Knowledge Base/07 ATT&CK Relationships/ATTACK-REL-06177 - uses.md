---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1593"
stix_relationship_id: "relationship--eba94ce8-cfb7-415d-a990-10c91d90d3e2"
---
# Relationship 6177: G0099 — uses → T1593

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1593 - Search Open Websites-Domains|T1593: Search Open Websites/Domains]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has gathered information on Colombian financial institutions, including Bancolombia, BBVA, Banco Caja Social, and Davivienda to craft phishing pages.(Citation: LevelBlue Blind Eagle Proton66 JUN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eba94ce8-cfb7-415d-a990-10c91d90d3e2`.
