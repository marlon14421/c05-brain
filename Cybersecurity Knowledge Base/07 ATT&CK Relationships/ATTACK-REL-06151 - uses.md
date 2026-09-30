---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0089"
target_object: "T1566.001"
stix_relationship_id: "relationship--e3d8a792-5c54-4e37-9ce1-6a8555e76a03"
---
# Relationship 6151: G0089 — uses → T1566.001

**Source object:** [[01 ATT&CK/G0089 - The White Company|G0089: The White Company]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[The White Company](https://attack.mitre.org/groups/G0089) has sent phishing emails with malicious Microsoft Word attachments to victims.(Citation: Cylance Shaheen Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3d8a792-5c54-4e37-9ce1-6a8555e76a03`.
