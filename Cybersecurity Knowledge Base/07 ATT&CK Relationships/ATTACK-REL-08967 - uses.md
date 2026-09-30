---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0026"
target_object: "T1102.002"
stix_relationship_id: "relationship--bb8149a2-fdda-4c3a-9e02-f530c4ee7962"
---
# Relationship 8967: S0026 — uses → T1102.002

**Source object:** [[01 ATT&CK/S0026 - GLOOXMAIL|S0026: GLOOXMAIL]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102.002 - Bidirectional Communication|T1102.002: Bidirectional Communication]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GLOOXMAIL](https://attack.mitre.org/software/S0026) communicates to servers operated by Google using the Jabber/XMPP protocol.(Citation: Mandiant APT1)(Citation: CyberESI GTALK)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb8149a2-fdda-4c3a-9e02-f530c4ee7962`.
