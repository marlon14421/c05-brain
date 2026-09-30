---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0059"
target_object: "T1608.005"
stix_relationship_id: "relationship--110fd4fd-3b1c-47d4-9e23-fb6b5346fc5e"
---
# Relationship 5291: C0059 — uses → T1608.005

**Source object:** [[01 ATT&CK/C0059 - Salesforce Data Exfiltration|C0059: Salesforce Data Exfiltration]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.005 - Link Target|T1608.005: Link Target]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Salesforce Data Exfiltration](https://attack.mitre.org/campaigns/C0059), threat actors established an Okta phishing panel which victims were tricked into accessing from mobile phones or work computers during social engineering calls.(Citation: FBI Salesforce Data Theft SEP 2025)(Citation: Google Salesforce JUN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--110fd4fd-3b1c-47d4-9e23-fb6b5346fc5e`.
