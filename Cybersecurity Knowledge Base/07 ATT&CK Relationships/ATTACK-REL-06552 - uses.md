---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1194"
target_object: "T1083"
stix_relationship_id: "relationship--b7cd4d27-492d-4abf-8fee-27e2449ba26d"
---
# Relationship 6552: S1194 — uses → T1083

**Source object:** [[01 ATT&CK/S1194 - Akira _v2|S1194: Akira _v2]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Akira _v2](https://attack.mitre.org/software/S1194) can target specific files and folders for encryption.(Citation: CISA Akira Ransomware APR 2024)(Citation: Cisco Akira Ransomware OCT 2024)(Citation: Palo Alto Howling Scorpius DEC 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7cd4d27-492d-4abf-8fee-27e2449ba26d`.
