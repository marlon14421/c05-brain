---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0250"
target_object: "T1059.003"
stix_relationship_id: "relationship--8674de47-b051-4384-a6e0-aeed32b8c270"
---
# Relationship 8956: S0250 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0250 - Koadic|S0250: Koadic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Koadic](https://attack.mitre.org/software/S0250) can open an interactive command-shell to perform command line functions on victim machines. [Koadic](https://attack.mitre.org/software/S0250) performs most of its operations using Windows Script Host (Jscript) and to run arbitrary shellcode.(Citation: Github Koadic)(Citation: MalwareBytes LazyScripter Feb 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8674de47-b051-4384-a6e0-aeed32b8c270`.
