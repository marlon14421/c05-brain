---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1050"
target_object: "T1218.015"
stix_relationship_id: "relationship--1803c9d0-8c13-461d-be06-68aa40901bce"
---
# Relationship 1389: M1050 — mitigates → T1218.015

**Source object:** [[01 ATT&CK/M1050 - Exploit Protection|M1050: Exploit Protection]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1218.015 - Electron Applications|T1218.015: Electron Applications]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Microsoft's Enhanced Mitigation Experience Toolkit (EMET) Attack Surface Reduction (ASR) feature can be used to block methods of using trusted binaries to bypass application control. Ensure that Electron is updated to the latest version and critical vulnerabilities (such as nodeIntegration bypasses) are patched and cannot be exploited.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1803c9d0-8c13-461d-be06-68aa40901bce`.
