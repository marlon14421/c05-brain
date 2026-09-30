---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-73"
status: "Draft"
---
# CWE-73: External Control of File Name or Path

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** Not Language-Specific, Unix, Windows, macOS

## Description

The product allows user input to control or influence paths or file names that are used in filesystem operations.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** When the set of filenames is limited or known, create a mapping from a set of fixed input values (such as numeric IDs) to the actual filenames, and reject all other inputs. For example, ID 1 could map to "inbox.txt" and ID 2 could map to "profile.txt". Features such as the ESAPI AccessReferenceMap provide this capability.
- **Architecture and Design:** For any security checks that are performed on the client side, ensure that these checks are duplicated on the server side, in order to avoid CWE-602. Attackers can bypass the client-side checks by modifying values after the checks have been performed, or by changing the client to remove the client-side checks entirely. Then, these modified values would be submitted to the server.
- **Implementation:** Use a built-in path canonicalization function (such as realpath() in C) that produces the canonical version of the pathname, which effectively removes ".." sequences and symbolic links (CWE-23, CWE-59).
- **Installation:** Use OS-level permissions and run as a low-privileged user to limit the scope of any successful attack.
- **Operation:** If you are using PHP, configure your application so that it does not use register_globals. During implementation, develop your application so that it does not rely on this feature, but be wary of implementing a register_globals emulation that is subject to weaknesses such as CWE-95, CWE-621, and similar issues.
- **Testing:** Use tools and techniques that require manual (human) analysis, such as penetration testing, threat modeling, and interactive tools that allow the tester to record and modify an active session. These may be more effective than strictly automated techniques. This is especially the case with weaknesses that are related to design and business rules.

## Related weaknesses

- CWE-642 (ChildOf)
- CWE-610 (ChildOf)
- CWE-20 (ChildOf)
- CWE-22 (CanPrecede)
- CWE-41 (CanPrecede)
- CWE-98 (CanPrecede)
- CWE-434 (CanPrecede)
- CWE-59 (CanPrecede)

## Source

- [CWE-73 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/73.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
