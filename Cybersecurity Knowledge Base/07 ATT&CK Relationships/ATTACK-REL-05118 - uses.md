---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0204"
target_object: "T1543.003"
stix_relationship_id: "relationship--0b4cd78b-e0af-4123-b2aa-02ad66cca419"
---
# Relationship 5118: S0204 — uses → T1543.003

**Source object:** [[01 ATT&CK/S0204 - Briba|S0204: Briba]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Briba](https://attack.mitre.org/software/S0204) installs a service pointing to a malicious DLL dropped to disk.(Citation: Symantec Briba May 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0b4cd78b-e0af-4123-b2aa-02ad66cca419`.
