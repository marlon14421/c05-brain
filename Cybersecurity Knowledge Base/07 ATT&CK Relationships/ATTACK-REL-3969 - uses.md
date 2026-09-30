---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0251"
target_object: "T1083"
stix_relationship_id: "relationship--86b7bab7-a1d6-4820-be55-c379f3967f1a"
---
# Relationship 3969: S0251 — uses → T1083

**Source object:** [[01 ATT&CK/S0251 - Zebrocy|S0251: Zebrocy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Zebrocy](https://attack.mitre.org/software/S0251) searches for files that are 60mb and less and contain the following extensions: .doc, .docx, .xls, .xlsx, .ppt, .pptx, .exe, .zip, and .rar. [Zebrocy](https://attack.mitre.org/software/S0251) also runs the echo %APPDATA% command to list the contents of the directory.(Citation: Securelist Sofacy Feb 2018)(Citation: ESET Zebrocy Nov 2018)(Citation: ESET Zebrocy May 2019) [Zebrocy](https://attack.mitre.org/software/S0251) can obtain the current execution path as well as perform drive enumeration.(Citation: Accenture SNAKEMACKEREL Nov 2018)(Citation: CISA Zebrocy Oct 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86b7bab7-a1d6-4820-be55-c379f3967f1a`.
