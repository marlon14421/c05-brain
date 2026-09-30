---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1025"
target_object: "T1547.005"
stix_relationship_id: "relationship--43bcf0ae-d0ff-4653-93c7-0c03eee5e5c2"
---
# Relationship 1107: M1025 — mitigates → T1547.005

**Source object:** [[01 ATT&CK/M1025 - Privileged Process Integrity|M1025: Privileged Process Integrity]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1547.005 - Security Support Provider|T1547.005: Security Support Provider]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Windows 8.1, Windows Server 2012 R2, and later versions may make LSA run as a Protected Process Light (PPL) by setting the Registry key HKLM\\SYSTEM\\CurrentControlSet\\Control\\Lsa\\RunAsPPL , which requires all SSP DLLs to be signed by Microsoft. (Citation: Graeber 2014) (Citation: Microsoft Configure LSA)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43bcf0ae-d0ff-4653-93c7-0c03eee5e5c2`.
