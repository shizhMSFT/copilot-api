# Charter

## Metadata

| Field | Value |
|-------|-------|
| Rulebook Name | Mixed-Stack Modernization Policy |
| Version | 1.0 |

## Scope

### Covered Applications and Languages

Java, .NET, and TypeScript applications are in scope.

## Modernization Strategy (6R Guidelines)

Of the 6R strategies, this rulebook covers **Rehost**, **Replatform**, and **Refactor** — the three that involve app modernization. Retire, Retain, and Repurchase are outside the scope of app modernization.

Supported strategies: **Rehost** (lift-and-shift, no code changes), **Replatform** (minimal code changes — containerize, adopt managed services), **Refactor** (modify code/architecture — decompose, upgrade).

| Application Type | Default Strategy | Override Conditions |
|------------------|-----------------|---------------------|
| Java application | Replatform | Deploy to Azure Container Apps |
| .NET application | Replatform | Deploy to Azure Container Apps |
| TypeScript service | Replatform | Deploy to Azure Container Apps |
