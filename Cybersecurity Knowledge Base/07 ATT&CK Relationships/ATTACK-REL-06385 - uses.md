---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0018"
target_object: "T1105"
stix_relationship_id: "relationship--e5421609-48cf-4e8e-8843-de6043e920f4"
---
# Relationship 6385: C0018 — uses → T1105

**Source object:** [[01 ATT&CK/C0018 - C0018|C0018: C0018]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0018](https://attack.mitre.org/campaigns/C0018), the threat actors downloaded additional tools, such as [Mimikatz](https://attack.mitre.org/software/S0002) and [Sliver](https://attack.mitre.org/software/S0633), as well as [Cobalt Strike](https://attack.mitre.org/software/S0154) and [AvosLocker](https://attack.mitre.org/software/S1053) ransomware onto the victim network.(Citation: Cisco Talos Avos Jun 2022)(Citation: Costa AvosLocker May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e5421609-48cf-4e8e-8843-de6043e920f4`.
