---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0377"
target_object: "T1554"
stix_relationship_id: "relationship--8d90820b-fd91-4452-aa91-50b783c2da38"
---
# Relationship 5894: S0377 — uses → T1554

**Source object:** [[01 ATT&CK/S0377 - Ebury|S0377: Ebury]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ebury](https://attack.mitre.org/software/S0377) modifies the `keyutils` library to add malicious behavior to the OpenSSH client and the curl library.(Citation: ESET Ebury Feb 2014)(Citation: ESET Ebury May 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8d90820b-fd91-4452-aa91-50b783c2da38`.
