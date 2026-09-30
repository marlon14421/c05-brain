---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1054"
target_object: "T1559.002"
stix_relationship_id: "relationship--9912d67b-153f-428e-9751-e6c09c8de945"
---
# Relationship 0282: M1054 — mitigates → T1559.002

**Source object:** [[01 ATT&CK/M1054 - Software Configuration|M1054: Software Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1559.002 - Dynamic Data Exchange|T1559.002: Dynamic Data Exchange]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider disabling embedded files in Office programs, such as OneNote, that do not work with Protected View.(Citation: Enigma Reviving DDE Jan 2018)(Citation: GitHub Disable DDEAUTO Oct 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9912d67b-153f-428e-9751-e6c09c8de945`.
