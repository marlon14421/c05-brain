---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0099"
target_object: "T1564.003"
stix_relationship_id: "relationship--da940fad-4778-4d61-b030-9618512c3537"
---
# Relationship 8047: G0099 — uses → T1564.003

**Source object:** [[01 ATT&CK/G0099 - APT-C-36|G0099: APT-C-36]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT-C-36](https://attack.mitre.org/groups/G0099) has set the ShowWindow property of the Win32_ProcessStartup object to zero to hide PowerShell execution.(Citation: Zscaler BlindEagle DEC 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--da940fad-4778-4d61-b030-9618512c3537`.
