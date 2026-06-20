# Security Policy

Playwright Case Studio is in the foundation phase and has not published a production-ready release.

Do not post private test environments, account information, screenshots, traces, or detailed security material in public Issues. Use GitHub private reporting when available. Otherwise open a minimal Issue requesting a private communication channel.

Reports should identify the affected commit, operating system, browser version, reproduction steps, observed impact, and a sanitized fixture.

Sensitive areas include stored test values, local project paths, uploaded files, downloaded files, reports, traces, and actions that can change application state.

The application should make target environments and executable steps visible, use controlled test fixtures, and avoid repeating irreversible actions without review.

Validated reports will be reviewed privately where practical. Public notes should identify affected versions and corrections without exposing test data.