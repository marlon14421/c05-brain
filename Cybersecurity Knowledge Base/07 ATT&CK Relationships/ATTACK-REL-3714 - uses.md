---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0690"
target_object: "T1543.001"
stix_relationship_id: "relationship--b6f451a7-f3a8-4d62-a449-21af7731d369"
---
# Relationship 3714: S0690 — uses → T1543.001

**Source object:** [[01 ATT&CK/S0690 - Green Lambert|S0690: Green Lambert]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.001 - Launch Agent|T1543.001: Launch Agent]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Green Lambert](https://attack.mitre.org/software/S0690) can create a [Launch Agent](https://attack.mitre.org/techniques/T1543/001) with the `RunAtLoad` key-value pair set to true , ensuring the `com.apple.GrowlHelper.plist` file runs every time a user logs in.(Citation: Objective See Green Lambert for OSX Oct 2021)(Citation: Glitch-Cat Green Lambert ATTCK Oct 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b6f451a7-f3a8-4d62-a449-21af7731d369`.
