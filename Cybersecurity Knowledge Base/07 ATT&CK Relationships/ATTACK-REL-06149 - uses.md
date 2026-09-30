---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0067"
target_object: "T1566.001"
stix_relationship_id: "relationship--d0061edc-becf-4ce9-ae91-5e1816d4a894"
---
# Relationship 6149: G0067 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0067 - APT37|G0067: APT37]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT37](https://attack.mitre.org/groups/G0067) delivers malware using spearphishing emails with malicious HWP attachments.(Citation: FireEye APT37 Feb 2018)(Citation: Talos Group123)(Citation: Securelist ScarCruft May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d0061edc-becf-4ce9-ae91-5e1816d4a894`.
