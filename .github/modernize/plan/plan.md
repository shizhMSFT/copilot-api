# Modernization Plan: Upgrade to .NET 10

**Project**: copilot-api

---

## Technical Framework

- **Language**: .NET (target: net10.0)
- **Framework**: ASP.NET Core
- **Build Tool**: dotnet CLI
- **Database**: N/A
- **Key Dependencies**: N/A

---

## Overview

> This migration upgrades the application runtime to .NET 10, the latest Long-Term Support (LTS) release. The upgrade ensures the application benefits from the latest performance improvements, security patches, and platform features available in .NET 10.
>
> The new architecture will:
>
> - Run on .NET 10 (net10.0), the current latest LTS version
> - Benefit from improved runtime performance and reduced memory footprint
> - Receive long-term security and maintenance support
>
> The migration follows a single-phase approach: upgrade the runtime and project targets, then remediate any CVEs introduced or exposed by the version change.

---

## Migration Impact Summary

| Application  | Original Service  | New Azure Service | Authentication     | Comments                    |
|--------------|-------------------|-------------------|--------------------|------------------------------|
| copilot-api  | .NET (current)    | .NET 10 (net10.0) | N/A                | Upgrade to latest LTS        |

---
