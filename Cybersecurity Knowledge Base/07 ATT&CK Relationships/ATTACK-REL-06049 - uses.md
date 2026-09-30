---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0394"
target_object: "T1037.004"
stix_relationship_id: "relationship--7ced0df2-1d05-40ea-986e-28692c028d92"
---
# Relationship 6049: S0394 — uses → T1037.004

**Source object:** [[01 ATT&CK/S0394 - HiddenWasp|S0394: HiddenWasp]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1037.004 - RC Scripts|T1037.004: RC Scripts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HiddenWasp](https://attack.mitre.org/software/S0394) installs reboot persistence by adding itself to /etc/rc.local .(Citation: Intezer HiddenWasp Map 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ced0df2-1d05-40ea-986e-28692c028d92`.
