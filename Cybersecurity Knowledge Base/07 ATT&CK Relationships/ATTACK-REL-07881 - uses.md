---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0650"
target_object: "T1566.001"
stix_relationship_id: "relationship--c191afcc-515a-4f0c-85cc-15af0fd3674a"
---
# Relationship 7881: S0650 — uses → T1566.001

**Source object:** [[01 ATT&CK/S0650 - QakBot|S0650: QakBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1566.001 - Spearphishing Attachment|T1566.001: Spearphishing Attachment]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QakBot](https://attack.mitre.org/software/S0650) has spread through emails with malicious attachments.(Citation: Trend Micro Qakbot May 2020)(Citation: Kroll Qakbot June 2020)(Citation: Trend Micro Qakbot December 2020)(Citation: Cyberint Qakbot May 2021)(Citation: ATT QakBot April 2021)(Citation: Kaspersky QakBot September 2021)(Citation: Group IB Ransomware September 2020)(Citation: Deep Instinct Black Basta August 2022)(Citation: Microsoft Ransomware as a Service)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c191afcc-515a-4f0c-85cc-15af0fd3674a`.
