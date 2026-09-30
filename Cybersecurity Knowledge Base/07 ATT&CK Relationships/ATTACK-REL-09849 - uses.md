---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9043"
target_object: "T1053.006"
stix_relationship_id: "relationship--43130352-f2d9-4a3f-8c9a-8ec46fce38d9"
---
# Relationship 9849: S9043 — uses → T1053.006

**Source object:** [[01 ATT&CK/S9043 - Mini Shai-Hulud|S9043: Mini Shai-Hulud]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.006 - Systemd Timers|T1053.006: Systemd Timers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has obtained persistence on Linux devices by writing the `gh-token-monitor` daemon within `~/.config/systemd/user/gh-token-monitor.service` that polls GitHub every 60 seconds.(Citation: Wiz Mini Shai-Hulud MAY 2026) [Mini Shai-Hulud](https://attack.mitre.org/software/S9043) has also leveraged a daemon called “kitty-monitor.service” to maintain persistence within Linux hosts.(Citation: Flashpoint Mini Shai-Hulud MAY 2026)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--43130352-f2d9-4a3f-8c9a-8ec46fce38d9`.
