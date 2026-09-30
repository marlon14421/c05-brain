---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0367"
target_object: "T1059.001"
stix_relationship_id: "relationship--7b458295-8e67-4f1f-acde-3316ae2e061e"
---
# Relationship 7545: S0367 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0367 - Emotet|S0367: Emotet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Emotet](https://attack.mitre.org/software/S0367) has used Powershell to retrieve the malicious payload and download additional resources like [Mimikatz](https://attack.mitre.org/software/S0002). (Citation: Symantec Emotet Jul 2018)(Citation: Trend Micro Emotet Jan 2019)(Citation: Picus Emotet Dec 2018)(Citation: Red Canary Emotet Feb 2019)(Citation: Carbon Black Emotet Apr 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7b458295-8e67-4f1f-acde-3316ae2e061e`.
