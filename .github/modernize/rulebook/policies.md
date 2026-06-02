# Policies

Enforceable standards and hard boundaries for mixed-stack modernization. Every policy here is validatable against generated artifacts.

## Security Requirements

### Authentication & Authorization

- All services must use Managed Identity for authentication to Azure services.

### Secrets Management

- Hard-coded credentials are prohibited. All secrets must be managed through approved secrets management services.

## Guardrails (Hard Boundaries)

### Prohibited Patterns

| Pattern | Reason | Approved Alternative |
|---------|--------|---------------------|
| Hard-coded credentials in source code or configuration | Security risk | Managed Identity; secrets management service |

### Required Elements

Every modernized application must include:

#### Cloud Resources

- Managed Identity assigned to the Azure Container Apps deployment.
