<!--
   - Copyright (C) 2019-2026
   - Julian Valentin, Daniel Spitzer, LTeX+ Development Community
   -
   - This Source Code Form is subject to the terms of the Mozilla Public
   - License, v. 2.0. If a copy of the MPL was not distributed with this
   - file, You can obtain one at https://mozilla.org/MPL/2.0/.
   -->

# Security Policy

This policy applies to all repositories of the [LT<sub>E</sub>X+ organization](https://github.com/ltex-plus) that do not have a security policy of their own. It says which versions get security fixes and how to report a vulnerability.

## Supported Versions

Only the latest published release of each project gets security fixes. The maintainers may also fix older releases when a vulnerability is severe and users need to keep the older release for compatibility.

## Definition of Vulnerabilities

LT<sub>E</sub>X+ follows [Microsoft's definition of security vulnerabilities](https://learn.microsoft.com/en-us/previous-versions/tn-archive/cc751383(v=technet.10)). In this document, “vulnerability” means security vulnerability.

## Reporting a Vulnerability

**Please do not report vulnerabilities in public GitHub issues.**

Report them privately with the “Report a vulnerability” button in the Security tab of the affected repository ([instructions](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing/privately-reporting-a-security-vulnerability)). Only the maintainers can read the report.

LT<sub>E</sub>X+ is maintained by volunteers in their free time. We aim to answer within 15 days. If you get no answer by then, please send a follow-up message.

Please include as much of the following as you can:

- Type of issue (e.g., arbitrary file write, command injection, data sent to an unexpected server)
- The affected repository and version, or the tag, branch or commit
- Paths of the source files related to the issue
- Settings or configuration needed to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- The impact of the issue, including how an attacker might exploit it

## Handling of Reports

1. We confirm that we received the report.
2. We check whether the issue is a [vulnerability](#definition-of-vulnerabilities).
3. We prepare a fix and test it in a release that is not public.
4. We publish the fixed release and disclose the vulnerability (see below).

We keep you informed of each step.

## Disclosure

Vulnerabilities are disclosed when the fixed release is published, or 30 days after the report, whichever comes first. Until then, please do not disclose the vulnerability, and neither will we.

The disclosure is made as a GitHub security advisory in the affected repository and as an entry in its changelog. The reporter is credited unless they ask to stay anonymous, and is free to publish their own analysis after the disclosure.
