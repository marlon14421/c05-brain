---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0029"
target_object: "T1070"
stix_relationship_id: "relationship--25c038d5-7cba-4416-ac10-f1c893942042"
---
# Relationship 8169: C0029 — uses → T1070

**Source object:** [[01 ATT&CK/C0029 - Cutting Edge|C0029: Cutting Edge]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Cutting Edge](https://attack.mitre.org/campaigns/C0029), threat actors cleared logs to remove traces of their activity and restored compromised systems to a clean state to bypass manufacturer mitigations for CVE-2023-46805 and CVE-2024-21887.(Citation: Mandiant Cutting Edge Part 2 January 2024)(Citation: Volexity Ivanti Zero-Day Exploitation January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25c038d5-7cba-4416-ac10-f1c893942042`.
