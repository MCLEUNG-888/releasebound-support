# ReleaseBound — App Store Connect Metadata

Copy-ready values for App Store Connect. URLs below were confirmed live over HTTPS after GitHub Pages deployment.
Claims here match ReleaseBound V1 behavior: no persistent run-by-run history and no drift detection in this version.

## App Name
ReleaseBound

## Version
0.1.0

## Promotional Text (156/170 characters)
Build with AI. Verify independently. ReleaseBound checks build, tests, signing, packaging and evidence on your Mac, so you know what is truly ready to ship.

## Keywords (96/100 characters)
release,verification,AI,build,signing,packaging,evidence,baseline,readiness,Xcode,audit,QA,macOS

## Description (2992/4000 characters)
```text
ReleaseBound is independent release verification for AI-built software.

AI coding agents can report success, but a successful agent report is not independent proof that a release is ready to ship. ReleaseBound checks the release outcome for itself, on your Mac, so you can build with AI, verify independently, and ship with confidence.

ReleaseBound is not an AI code generator, coding assistant, or code reviewer. It is an independent verification layer that sits beside the tools you already use.

HOW IT WORKS
Choose a project, and ReleaseBound identifies the release candidate, runs the required gates, records evidence, and reports a single release verdict. Anything it cannot independently confirm is not treated as a pass.

WHAT IT VERIFIES
- Release candidate: verification is tied to a specific candidate of your project.
- Required gates: build, tests, source state, signing, and packaging.
- Evidence: the technical results behind each gate are shown in the app so a verdict can be inspected, not just trusted.
- Verified baseline: the most recent verified release is recorded as a Last Known Good baseline. ReleaseBound keeps the latest baseline only, not a history of runs.

CLEAR VERDICTS
Every run ends in an explicit verdict: NOT VERIFIED, READY, NOT READY, or BLOCKED. BLOCKED means a required fact could not be independently confirmed, so ReleaseBound does not report a pass.

LOCAL-FIRST
ReleaseBound is designed to work locally on your Mac against a project folder you choose. It does not require an account, and it contains no analytics, crash-reporting, or advertising SDKs. ReleaseBound's own code makes no network requests and does not transmit your project data. It runs Apple developer tools installed on your Mac (such as git and xcodebuild) on the project you choose, and it opens web pages such as the ReleaseBound support and legal pages in your browser only when you click a link. Developer tools invoked during verification may write result files, archives, or other build artifacts locally on your Mac. ReleaseBound may write a Verified Release Baseline file to a project folder you have explicitly authorized.

PLATFORM FOCUS
The initial focus is Apple platform development (macOS and iOS projects). Verification depends on your project type and the developer tools installed on your Mac, so not every verification mode applies to every language or platform.

LIMITATIONS
ReleaseBound reports only what it can independently confirm. It does not guarantee that software is free of defects or vulnerabilities, does not eliminate release risk, and is not a legal, security, or compliance certification. The decision to release always remains yours.

LINKS
Support: https://mcleung-888.github.io/releasebound-support/support/
Privacy Policy: https://mcleung-888.github.io/releasebound-support/privacy/
Terms of Use: https://mcleung-888.github.io/releasebound-support/terms/
Apple Standard EULA: https://www.apple.com/legal/internet-services/itunes/dev/stdeula/
```

## URLs
| Field | Value |
| --- | --- |
| Support URL | https://mcleung-888.github.io/releasebound-support/support/ |
| Marketing URL | https://mcleung-888.github.io/releasebound-support/ |
| Privacy Policy URL | https://mcleung-888.github.io/releasebound-support/privacy/ |
| Terms of Use URL | https://mcleung-888.github.io/releasebound-support/terms/ |
| EULA | https://www.apple.com/legal/internet-services/itunes/dev/stdeula/ (Apple Standard EULA; no custom EULA) |

## App Privacy: Data Collection
No data collected. ReleaseBound's own code makes no network requests, contains no analytics, crash-reporting, or advertising SDK, and does not transmit project or personal data.

## Copyright
COPYRIGHT_NEEDS_PRODUCT_OWNER_CONFIRMATION

No repository evidence confirms the name to use. If appropriate, the Product Owner may enter `2026 <legal name>` in App Store Connect.
