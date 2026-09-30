---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0387"
target_object: "T1543.003"
stix_relationship_id: "relationship--2b26c652-7f0e-41f1-810a-7e6c24f2bfdb"
---
# Relationship 9340: S0387 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0387 - KeyBoy|S0387: KeyBoy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KeyBoy](https://attack.mitre.org/software/S0387) installs a service pointing to a malicious DLL dropped to disk.(Citation: Rapid7 KeyBoy Jun 2013)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b26c652-7f0e-41f1-810a-7e6c24f2bfdb`.
