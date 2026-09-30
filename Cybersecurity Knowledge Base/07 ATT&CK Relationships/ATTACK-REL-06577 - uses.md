---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0001"
target_object: "T1140"
stix_relationship_id: "relationship--d87615c7-501a-4b78-87fb-ba2c1a2faffb"
---
# Relationship 6577: C0001 — uses → T1140

**Source object:** [[01 ATT&CK/C0001 - Frankenstein|C0001: Frankenstein]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [Frankenstein](https://attack.mitre.org/campaigns/C0001), the threat actors deobfuscated Base64-encoded commands following the execution of a malicious script, which revealed a small script designed to obtain an additional payload.(Citation: Talos Frankenstein June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d87615c7-501a-4b78-87fb-ba2c1a2faffb`.
