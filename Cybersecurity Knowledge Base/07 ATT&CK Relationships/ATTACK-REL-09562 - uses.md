---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1153"
target_object: "T1553.001"
stix_relationship_id: "relationship--c8420a85-8724-450c-858e-217cdab58df8"
---
# Relationship 9562: S1153 — uses → T1553.001

**Source object:** [[01 ATT&CK/S1153 - Cuckoo Stealer|S1153: Cuckoo Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.001 - Gatekeeper Bypass|T1553.001: Gatekeeper Bypass]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cuckoo Stealer](https://attack.mitre.org/software/S1153) can use `xattr -d com.apple.quarantine` to remove the quarantine flag attribute.(Citation: Kandji Cuckoo April 2024)(Citation: SentinelOne Cuckoo Stealer May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8420a85-8724-450c-858e-217cdab58df8`.
