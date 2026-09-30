---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0154"
target_object: "T1059.001"
stix_relationship_id: "relationship--7396dd25-432c-4285-8149-1237b1273a53"
---
# Relationship 5966: S0154 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0154 - Cobalt Strike|S0154: Cobalt Strike]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cobalt Strike](https://attack.mitre.org/software/S0154) can execute a payload on a remote host with PowerShell. This technique does not write any data to disk.(Citation: cobaltstrike manual)(Citation: Cyberreason Anchor December 2019) [Cobalt Strike](https://attack.mitre.org/software/S0154) can also use [PowerSploit](https://attack.mitre.org/software/S0194) and other scripting frameworks to perform execution.(Citation: Cobalt Strike TTPs Dec 2017)(Citation: CobaltStrike Daddy May 2017)(Citation: Talos Cobalt Strike September 2020)(Citation: Cobalt Strike Manual 4.3 November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7396dd25-432c-4285-8149-1237b1273a53`.
