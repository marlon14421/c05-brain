---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0356"
target_object: "T1082"
stix_relationship_id: "relationship--172da5b1-cf68-468a-8208-b15ea5c813dc"
---
# Relationship 6936: S0356 — uses → T1082

**Source object:** [[01 ATT&CK/S0356 - KONNI|S0356: KONNI]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KONNI](https://attack.mitre.org/software/S0356) can gather the OS version, architecture information, hostname, and RAM size information from the victim’s machine and has used cmd /c systeminfo command to get a snapshot of the current system state of the target machine.(Citation: Talos Konni May 2017)(Citation: Medium KONNI Jan 2020)(Citation: Malwarebytes Konni Aug 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--172da5b1-cf68-468a-8208-b15ea5c813dc`.
