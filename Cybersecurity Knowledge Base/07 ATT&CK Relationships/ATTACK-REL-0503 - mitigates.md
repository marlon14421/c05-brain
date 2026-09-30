---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1553"
stix_relationship_id: "relationship--d9c08e10-909d-46d0-aa15-b99d1487be62"
---
# Relationship 0503: M1054 — mitigates → T1553

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1553 - Subvert Trust Controls|T1553: Subvert Trust Controls]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

HTTP Public Key Pinning (HPKP) is one method to mitigate potential [Adversary-in-the-Middle](https://attack.mitre.org/techniques/T1557) situations where and adversary uses a mis-issued or fraudulent certificate to intercept encrypted communications by enforcing use of an expected certificate. (Citation: Wikipedia HPKP)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d9c08e10-909d-46d0-aa15-b99d1487be62`.
