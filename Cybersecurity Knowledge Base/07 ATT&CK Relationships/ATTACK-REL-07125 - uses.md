---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0070"
target_object: "T1574.001"
stix_relationship_id: "relationship--1762fe5a-0810-4179-bfb0-16d965ffe055"
---
# Relationship 7125: S0070 — uses → T1574.001

**Source object:** [[01 ATT&CK/S0070 - HTTPBrowser|S0070: HTTPBrowser]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.001 - DLL|T1574.001: DLL]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HTTPBrowser](https://attack.mitre.org/software/S0070) abuses the Windows DLL load order by using a legitimate Symantec anti-virus binary, VPDN_LU.exe, to load a malicious DLL that mimics a legitimate Symantec DLL, navlu.dll.(Citation: ZScaler Hacking Team) [HTTPBrowser](https://attack.mitre.org/software/S0070) has also used DLL side-loading.(Citation: Dell TG-3390)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1762fe5a-0810-4179-bfb0-16d965ffe055`.
