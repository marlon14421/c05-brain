---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9011"
target_object: "T1205"
stix_relationship_id: "relationship--bf16e2d4-6d9a-4487-882a-776012a21831"
---
# Relationship 9900: S9011 — uses → T1205

**Source object:** [[01 ATT&CK/S9011 - BRUSHFIRE|S9011: BRUSHFIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1205 - Traffic Signaling|T1205: Traffic Signaling]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BRUSHFIRE](https://attack.mitre.org/software/S9011) has monitored inbound VPN traffic to compromised appliances until specific inbound packets contain a specific magic string/pattern instead of external beaconing.(Citation: Picus Security UNC5221 Ivanti May 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bf16e2d4-6d9a-4487-882a-776012a21831`.
