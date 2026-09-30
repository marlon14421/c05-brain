---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9008"
target_object: "T1608.001"
stix_relationship_id: "relationship--b27d69e9-d7e0-4d06-88e4-942b42987028"
---
# Relationship 9801: S9008 — uses → T1608.001

**Source object:** [[01 ATT&CK/S9008 - Shai-Hulud|S9008: Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.001 - Upload Malware|T1608.001: Upload Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Shai-Hulud](https://attack.mitre.org/software/S9008) has published malicious gzip-compressed tarball (.tgz) following modification of packages within compromised accounts.(Citation: Aikido Shai-Hulud September 2025)(Citation: Socket Shai-Hulud Trufflehog September 2025) [Shai-Hulud](https://attack.mitre.org/software/S9008) has also modified packages within compromised accounts.(Citation: Netskope Shai-Hulud November 2025)(Citation: Wiz Shai-Hulud September 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b27d69e9-d7e0-4d06-88e4-942b42987028`.
