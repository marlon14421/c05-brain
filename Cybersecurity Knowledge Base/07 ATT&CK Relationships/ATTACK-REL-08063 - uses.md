---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1569.002"
stix_relationship_id: "relationship--08a0175a-eb34-4ed2-a9ca-d458da65326a"
---
# Relationship 8063: S1111 — uses → T1569.002

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) tries to elevate privileges to SYSTEM using PsExec to locally execute as a service, such as cmd /c c:\temp\PsExec.exe -accepteula -j -d -s [Target Binary] .(Citation: Trellix Darkgate 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--08a0175a-eb34-4ed2-a9ca-d458da65326a`.
