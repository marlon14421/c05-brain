---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0002"
target_object: "T1134.005"
stix_relationship_id: "relationship--3e5cf341-4707-4de3-bb06-43530ee3e90f"
---
# Relationship 6926: S0002 — uses → T1134.005

**Source object:** [[01 ATT&CK/S0002 - Mimikatz|S0002: Mimikatz]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1134.005 - SID-History Injection|T1134.005: SID-History Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mimikatz](https://attack.mitre.org/software/S0002)'s MISC::AddSid module can append any SID or user/group account to a user's SID-History. [Mimikatz](https://attack.mitre.org/software/S0002) also utilizes [SID-History Injection](https://attack.mitre.org/techniques/T1134/005) to expand the scope of other components such as generated Kerberos Golden Tickets and DCSync beyond a single domain.(Citation: Adsecurity Mimikatz Guide)(Citation: AdSecurity Kerberos GT Aug 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3e5cf341-4707-4de3-bb06-43530ee3e90f`.
