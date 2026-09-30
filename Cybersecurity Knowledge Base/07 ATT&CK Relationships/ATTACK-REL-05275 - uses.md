---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0059"
target_object: "T1585.002"
stix_relationship_id: "relationship--5f7853bd-a4d6-418f-8d23-d24fc32dffa0"
---
# Relationship 5275: C0059 — uses → T1585.002

**Source object:** [[01 ATT&CK/C0059 - Salesforce Data Exfiltration|C0059: Salesforce Data Exfiltration]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1585.002 - Email Accounts|T1585.002: Email Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Salesforce Data Exfiltration](https://attack.mitre.org/campaigns/C0059), threat actors registered emails shinycorp@tuta[.]com and shinygroup@tuta[.]com to send victims extortion demands.(Citation: Google Salesforce JUN 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f7853bd-a4d6-418f-8d23-d24fc32dffa0`.
