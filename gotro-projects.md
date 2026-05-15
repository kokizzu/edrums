# Gotro Projects Comparison

This table compares only common, non-project-specific platform features across these projects:

- `tacticduar`
- `street`
- `kostjc`
- `benakun`

Domain-specific business features are intentionally excluded.

## `tacticduar` Missing Or Incomplete

| Feature | tacticduar | street | kostjc | benakun | Status for `tacticduar` |
|---|---|---|---|---|---|
| Deactivate own account | No | Yes | No | No | Missing vs `street` only |
| Admin access/user audit logs | No | Yes | Yes | Yes | Missing |
| Dashboard landing for admin role | No | Yes | No | Yes | Optional missing |
| Backup command | No | Yes | Yes | No | Missing vs `street`,`kostjc` |
| Restore command | No | Yes | Yes | No | Missing vs `street`,`kostjc` |
| Stats/maintenance command | No | Yes | Yes | No | Missing vs `street`,`kostjc` |
| Production `deploy/` scaffolding | No | Yes | Yes | No | Missing |
| Setup/ops README | Minimal | Yes | Minimal | Minimal | Missing/incomplete |

## `tacticduar` Is `Yes`

| Feature | tacticduar | street | kostjc | benakun | Status for `tacticduar` |
|---|---|---|---|---|---|
| Login | Yes | Yes | Yes | Yes | Present |
| Register | Yes | Yes | Yes | Yes | Present |
| Resend verification email | Yes | Yes | Yes | Yes | Present |
| Verify email | Yes | Yes | Yes | Yes | Present |
| Reset password | Yes | Yes | Yes | Yes | Present |
| Forgot-password request/initiation | Yes | Yes | No | Yes | Present |
| Logout | Yes | Yes | Yes | Yes | Present |
| User profile view | Yes | Yes | Yes | Yes | Present |
| User profile update | Yes | Yes | Yes | Yes | Present |
| Change password while logged in | Yes | Yes | No | Yes | Present |
| Active sessions list | Yes | Yes | Yes | Yes | Present |
| Kill session | Yes | Yes | Yes | Yes | Present |
| Basic admin user management | Yes | Yes | Yes | Yes | Present |
| OAuth/external auth start | Yes | Yes | No | Yes | Present, but not universal |
| OAuth callback/token exchange | Yes | Yes | No | Partial | Present, but not universal |
| Auto-login consume flow | Yes | Yes | Partial | Yes | Present |
| Auto-login link generation | Yes | Yes | Yes | Yes | Present |
| Generic file endpoint/upload | Yes | Yes | No | No | Present, but not universal |
| Debug endpoint/page | Yes | Yes | No | Yes | Present, but not universal |

## Main Common Gaps In `tacticduar`

Strongly supported by at least one comparison project:

1. Admin access/user audit logs
2. Backup/restore/stat maintenance commands
3. Production deploy scaffolding
4. Better setup/ops documentation

Less clearly common:

1. `UserDeactivate` exists in `street` only
2. Admin dashboard landing exists in `street` and `benakun`, but not `kostjc`

## Important Dependency Differences

These are the more important library/runtime differences, especially around the shared stack.

| Area | tacticduar | street | kostjc | benakun |
|---|---|---|---|---|
| Go version | `1.25.3` | `1.25.5` | `1.24.1` | `1.22.0` + `toolchain go1.23.1` |
| `gotro` | `v1.5825.2021` | `v1.3503.236` | `v1.3503.236` | `v1.4501.2212` |
| Tarantool driver | `github.com/tarantool/go-tarantool v1.12.1` | `v1.12.2` | `v1.12.1` | `github.com/tarantool/go-tarantool/v2 v2.1.0` |
| ClickHouse driver | `github.com/ClickHouse/clickhouse-go/v2 v2.40.3` | `v2.42.0` | `v2.30.1` | `v2.28.3` |
| Fiber | `v2.50.0` | `v2.52.12` | `v2.50.0` | `v2.52.4` |
| OAuth2 | old pseudo-version `v0.0.0-20220524215830-622c5d57e401` | `v0.27.0` | old pseudo-version `v0.0.0-20220524215830-622c5d57e401` | old pseudo-version `v0.0.0-20220524215830-622c5d57e401` |
| Mail transport | `go-mail`, `mailhog`, `dockermailserver` | `go-mail`, `mailhog`, `dockermailserver`, `mailjet`, `sendgrid` | `go-mail`, `mailhog`, `dockermailserver` | `go-mail`, `mailhog`, `dockermailserver` |
| Timed log buffer | `ch-timed-buffer v1.2025.1416` | same | same | same |
| Session/token stack | `enkodo`, `fasthash`, `xxh3`, `lexid`, `id64` | same plus `jwt/v5` | same | same plus Tarantool v2 / `go-iproto` |
| Image/media helpers | `disintegration/imaging`, `mimetype`, `base62` | `mimetype`, `base62` | `mimetype` | `mimetype` |
| Worker/cache extras | `alitto/pond`, `allegro/bigcache/v3` | `allegro/bigcache/v3` | none direct in main require block | none direct in main require block |
| Import/report extras | none major | `excelize`, `gjson`, `tsvreader`, `lz4`, `mailjet`, `sendgrid` | `lz4` | `json5b` |

## Notes

- `Auto-login consume flow` is now marked present for `tacticduar` because both `UserAutoLoginLink` and `GuestAutoLogin` have been added.
- `Forgot-password request/initiation` and `UserChangePassword` are now present in `tacticduar`.
- `benakun` is the most divergent on the persistence side because it already uses `go-tarantool/v2`, while the others still use the v1 driver line.
