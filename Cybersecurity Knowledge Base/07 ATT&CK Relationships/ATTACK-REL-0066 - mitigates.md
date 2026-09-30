---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1490"
stix_relationship_id: "relationship--c4cd9acb-aaea-4b77-890e-f153a58623a4"
---
# Relationship 0066: M1028 — mitigates → T1490

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider technical controls to prevent the disabling of services or deletion of files involved in system recovery. Additionally, ensure that WinRE is enabled using the following command: reagentc /enable .(Citation: reagentc_cmd)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c4cd9acb-aaea-4b77-890e-f153a58623a4`.
