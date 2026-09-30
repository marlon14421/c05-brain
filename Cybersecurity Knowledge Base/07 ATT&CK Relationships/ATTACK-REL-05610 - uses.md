---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1105"
target_object: "T1574.006"
stix_relationship_id: "relationship--89871b65-3850-440a-8a6b-4ed78a24b13d"
---
# Relationship 5610: S1105 — uses → T1574.006

**Source object:** [[01 ATT&CK/S1105 - COATHANGER|S1105: COATHANGER]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1574.006 - Dynamic Linker Hijacking|T1574.006: Dynamic Linker Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[COATHANGER](https://attack.mitre.org/software/S1105) copies the malicious file /data2/.bd.key/preload.so to /lib/preload.so , then launches a child process that executes the malicious file /data2/.bd.key/authd as /bin/authd with the arguments /lib/preload.so reboot newreboot 1 .(Citation: NCSC-NL COATHANGER Feb 2024) This injects the malicious preload.so file into the process with PID 1, and replaces its reboot function with the malicious newreboot function for persistence.

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--89871b65-3850-440a-8a6b-4ed78a24b13d`.
