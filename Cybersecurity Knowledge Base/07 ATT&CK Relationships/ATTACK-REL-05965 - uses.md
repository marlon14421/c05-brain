---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1122"
target_object: "T1555"
stix_relationship_id: "relationship--e9cbcdd4-645d-45ee-a5b6-65c651afe154"
---
# Relationship 5965: S1122 — uses → T1555

**Source object:** [[01 ATT&CK/S1122 - Mispadu|S1122: Mispadu]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555 - Credentials from Password Stores|T1555: Credentials from Password Stores]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mispadu](https://attack.mitre.org/software/S1122) has obtained credentials from mail clients via NirSoft MailPassView.(Citation: SCILabs Malteiro 2021)(Citation: Segurança Informática URSA Sophisticated Loader 2020)(Citation: ESET Security Mispadu Facebook Ads 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9cbcdd4-645d-45ee-a5b6-65c651afe154`.
