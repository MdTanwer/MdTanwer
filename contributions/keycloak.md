# Keycloak (Red Hat)

[All pull requests](https://github.com/keycloak/keycloak/pulls/MdTanwer) · [Back to profile](../README.md)

Security and theme fixes in the identity server: client secrets, session cookies, request validation, and the FreeMarker theme layer.

**Overall:** 4 merged, 1 open, 4 closed without merge. The merged pull requests fix client-secret entropy (HS512), an inverted legacy `KEYCLOAK_SESSION` cookie comparison, path traversal in `FolderTheme.getTemplate()`, and unversioned FreeMarker engine defaults. The open pull request pins UBI base images by digest.

## Merged

| Pull request | Detail |
|---|---|
| [#50147](https://github.com/keycloak/keycloak/pull/50147) | Fix an inverted return value in the legacy `KEYCLOAK_SESSION` cookie comparison. |
| [#50099](https://github.com/keycloak/keycloak/pull/50099) | Use versioned FreeMarker `Configuration` defaults so the theme engine does not inherit unsafe defaults. |
| [#50098](https://github.com/keycloak/keycloak/pull/50098) | Enforce path containment in `FolderTheme.getTemplate()` to block path traversal. |
| [#50083](https://github.com/keycloak/keycloak/pull/50083) | Fix client-secret length so generated secrets always use HS512 entropy (~512 bits). |

## Open

| Pull request | Detail |
|---|---|
| [#50249](https://github.com/keycloak/keycloak/pull/50249) | Pin UBI base images by digest in container Dockerfiles. |

## Closed

| Pull request | Detail |
|---|---|
| [#50148](https://github.com/keycloak/keycloak/pull/50148) | Enforce allowed-protocol-mappers on Admin REST API protocol mapper operations. |
| [#50146](https://github.com/keycloak/keycloak/pull/50146) | Validate client URLs during partial import. |
| [#50145](https://github.com/keycloak/keycloak/pull/50145) | Pin UBI base images by digest in container Dockerfiles. |
| [#50109](https://github.com/keycloak/keycloak/pull/50109) | Return HTTP 400 for a malformed Content-Type header. |
