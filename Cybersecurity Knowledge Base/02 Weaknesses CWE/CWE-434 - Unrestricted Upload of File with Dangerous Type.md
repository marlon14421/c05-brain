---
type: "Weakness"
source: "MITRE CWE"
id: "CWE-434"
status: "Draft"
---
# CWE-434: Unrestricted Upload of File with Dangerous Type

**Abstraction:** Base  
**Status in catalog:** Draft  
**Applicable platforms:** ASP.NET, PHP, Not Language-Specific, Web Server, AI/ML

## Description

The product allows the upload or transfer of dangerous file types that are automatically processed within its environment.

## Defensive relevance

Use this weakness as a review and classification aid. Confirm the vulnerable condition in code or configuration, assess reachability and impact, and select a fix appropriate to the affected product. Catalog membership by itself does not establish exploitability.

## Mitigations in the catalog

- **Architecture and Design:** Generate a new, unique filename for an uploaded file instead of using the user-supplied filename, so that no external input is used at all.[REF-422] [REF-423]
- **Architecture and Design:** When the set of acceptable objects, such as filenames or URLs, is limited or known, create a mapping from a set of fixed input values (such as numeric IDs) to the actual filenames or URLs, and reject all other inputs.
- **Architecture and Design:** Consider storing the uploaded files outside of the web document root entirely. Then, use other mechanisms to deliver the files dynamically. [REF-423]
- **Architecture and Design:** Define a very limited set of allowable extensions and only generate filenames that end in these extensions. Consider the possibility of XSS (CWE-79) before allowing .html or .htm file types.
- **Implementation:** Ensure that only one extension is used in the filename. Some web servers, including some versions of Apache, may process files based on inner extensions so that "filename.php.gif" is fed to the PHP interpreter.[REF-422] [REF-423]
- **Implementation:** When running on a web server that supports case-insensitive filenames, perform case-insensitive evaluations of the extensions that are provided.
- **Architecture and Design:** For any security checks that are performed on the client side, ensure that these checks are duplicated on the server side, in order to avoid CWE-602. Attackers can bypass the client-side checks by modifying values after the checks have been performed, or by changing the client to remove the client-side checks entirely. Then, these modified values would be submitted to the server.
- **Implementation:** Do not rely exclusively on sanity checks of file contents to ensure that the file is of the expected type and size. It may be possible for an attacker to hide code in some file segments that will still be executed by the server. For example, GIF images may contain a free-form comments field.
- **Implementation:** Do not rely exclusively on the MIME content type or filename attribute when determining how to render a file. Validating the MIME content type and ensuring that it matches the extension is only a partial solution.
- **Architecture and Design:** Run your code using the lowest privileges that are required to accomplish the necessary tasks [REF-76]. If possible, create isolated accounts with limited privileges that are only used for a single task. That way, a successful attack will not immediately give the attacker access to the rest of the software or its environment. For example, database applications rarely need to run as the database administrator, especially in day-to-day operations.

## Related weaknesses

- CWE-669 (ChildOf)
- CWE-669 (ChildOf)
- CWE-351 (PeerOf)
- CWE-436 (PeerOf)
- CWE-430 (PeerOf)

## Source

- [CWE-434 on cwe.mitre.org](https://cwe.mitre.org/data/definitions/434.html)
- Dataset: [MITRE CWE catalog](https://cwe.mitre.org/data/downloads.html), version 4.20 (retrieved 2026-09-30).
