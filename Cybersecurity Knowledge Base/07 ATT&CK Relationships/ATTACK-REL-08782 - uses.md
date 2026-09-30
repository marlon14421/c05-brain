---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1614"
stix_relationship_id: "relationship--afb2acec-b781-4f8c-8268-d326d4f4f074"
---
# Relationship 8782: S1245 — uses → T1614

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614 - System Location Discovery|T1614: System Location Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has collected the internal IP address, IP geolocation information of the infected host and sends the data to a C2 server.(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023) [InvisibleFerret](https://attack.mitre.org/software/S1245) has also leveraged the “pay” module to obtain region name, country, city, zip code, ISP, latitude and longitude using “http://ip-api.com/json”.(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--afb2acec-b781-4f8c-8268-d326d4f4f074`.
