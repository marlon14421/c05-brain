---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-616"
status: "Incomplete"
---
# CWE-616: Incomplete Identification of Uploaded File Variables (PHP)

**Abstraction:** Variant  
**Status in catalog:** Incomplete  
**Applicable platforms:** PHP

## Description

The PHP application uses an old method for processing uploaded files by referencing the four global variables that are set for each file (e.g. $varname, $varname_size, $varname_name, $varname_type). These variables could be overwritten by attackers, causing the application to process unauthorized files.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Use PHP 4 or later.
- **Architecture and Design:** If you must support older PHP versions, write your own version of is_uploaded_file() and run it against $HTTP_POST_FILES['userfile']))
- **Implementation:** For later PHP versions, reference uploaded files using the $HTTP_POST_FILES or $_FILES variables, and use is_uploaded_file() or move_uploaded_file() to ensure that you are dealing with an uploaded file.

## Related weaknesses

- CWE-345 (ChildOf)
- CWE-473 (PeerOf)

## Source

- [CWE-616 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/616.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
