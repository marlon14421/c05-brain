---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1038"
target_object: "T1218.015"
stix_relationship_id: "relationship--4e1b6f6e-6741-45e7-856b-1efdb2f50ba3"
---
# Relationship 0346: M1038 — mitigates → T1218.015

**Source object:** [[01 ATT&CK/M1038 - Execution Prevention|M1038: Execution Prevention]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1218.015 - Electron Applications|T1218.015: Electron Applications]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Where possible, enforce binary and application integrity with digital signature verification to prevent untrusted code from executing. For example, do not use `shell.openExternal` with untrusted content. Where possible, set `nodeIntegration` to false, which disables access to the Node.js function.(Citation: Electron Security 3) By disabling access to the Node.js function, this may limit the ability to execute malicious commands by injecting JavaScript code. Do not disable `webSecurity`, which may allow for users of the application to invoke malicious content from online sources.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4e1b6f6e-6741-45e7-856b-1efdb2f50ba3`.
