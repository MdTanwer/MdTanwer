# Keycloak (Red Hat)

[All pull requests](https://github.com/keycloak/keycloak/pulls/MdTanwer) · [Back to profile](../README.md)

Security and theme fixes in the identity server: client secrets, session cookies, and the FreeMarker theme layer.

| Pull request | Detail |
|---|---|
| [#50098](https://github.com/keycloak/keycloak/pull/50098) | Enforce path containment in `FolderTheme.getTemplate()` to block path traversal. |
| [#50083](https://github.com/keycloak/keycloak/pull/50083) | Fix client-secret length so generated secrets always use HS512 entropy (~512 bits). |
| [#50147](https://github.com/keycloak/keycloak/pull/50147) | Fix an inverted return value in the legacy `KEYCLOAK_SESSION` cookie comparison. |
| [#50099](https://github.com/keycloak/keycloak/pull/50099) | Use versioned FreeMarker `Configuration` defaults so the theme engine does not inherit unsafe defaults. |
| [#50249](https://github.com/keycloak/keycloak/pull/50249) | Pin UBI base images by digest in container Dockerfiles. |
