---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1185"
target_object: "T1046"
stix_relationship_id: "relationship--c9c411dd-b313-4448-a2b9-17d00b3c78e2"
---
# Relationship 7650: S1185 — uses → T1046

**Source object:** [[01 ATT&CK/S1185 - LightSpy|S1185: LightSpy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

To collect data on the host's Wi-Fi connection history, [LightSpy](https://attack.mitre.org/software/S1185) reads the `/Library/Preferences/SystemConfiguration/com.apple.airport.preferences.plist file`.It also utilizes Apple's CWWiFiClient API to scan for nearby Wi-Fi networks and obtain data on the SSID, security type, and RSSI (signal strength) values.(Citation: Huntress LightSpy macOS 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9c411dd-b313-4448-a2b9-17d00b3c78e2`.
