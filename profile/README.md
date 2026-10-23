<p align="center">
  <a href="https://www.codeskop.com/?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io">
    <img src="https://www.codeskop.com/media/product-tour-poster.jpg" alt="Codeskop: crash, error and API monitoring for mobile, web and backend apps" width="720">
  </a>
</p>

<h1 align="center">Codeskop</h1>

<p align="center">
  <strong>Crash, error and API monitoring for mobile, web and backend apps.</strong><br>
  See what broke, who it hit and how to fix it.
</p>

<p align="center">
  <a href="https://www.codeskop.com/?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io">Website</a> ·
  <a href="https://www.codeskop.com/docs?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io">Docs</a> ·
  <a href="https://www.codeskop.com/pricing?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io">Pricing</a> ·
  <a href="https://dashboard.codeskop.com/signup?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io">Start free</a>
</p>

---

## What Codeskop does

- **Crashes and errors, grouped into issues.** Crashes, ANRs, JavaScript errors and backend exceptions, ranked by how many users they affect, not just how many events they send.
- **Failing and slow API calls.** Failed requests, status codes and timing next to your crashes, so silent failures count too.
- **Release health.** Crash-free users and sessions per release, new issues and regressions.
- **User journeys.** The crashes, errors and failed API calls a person hit, in order.
- **From issue to fix.** Alerts in Slack, Microsoft Teams, Discord, Telegram, WhatsApp, email or webhooks; tickets in Jira, Linear, GitHub Issues, Asana or ClickUp; and Fix with AI, which drafts a pull request.

Features vary by plan, and there is a free plan. See [pricing](https://www.codeskop.com/pricing?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io).

## SDKs

| Platform | Package | Links |
|---|---|---|
| Android | `com.codeskop.sdk:tracker-android` | [Docs](https://www.codeskop.com/docs/quickstart/android?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) |
| Kotlin Multiplatform and iOS (beta) | `com.codeskop.sdk:tracker-core` | [Docs](https://www.codeskop.com/docs/kmp?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) |
| Flutter | `codeskop_tracker` | [Docs](https://www.codeskop.com/docs/android/flutter?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) |
| Web (JavaScript, React) | `@codeskop/tracker`, `@codeskop/tracker-react` | [Docs](https://www.codeskop.com/docs/web/installation?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) · [web-sdk](https://github.com/Codeskop-io/web-sdk) |
| Go | `github.com/Codeskop-io/codeskop-go` | [Docs](https://www.codeskop.com/docs/server/go?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) · [codeskop-go](https://github.com/Codeskop-io/codeskop-go) |
| Python | `codeskop` | [Docs](https://www.codeskop.com/docs/server/python?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) · [codeskop-python](https://github.com/Codeskop-io/codeskop-python) |
| Node.js | `@codeskop/node` | [Docs](https://www.codeskop.com/docs/server/node?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) · [codeskop-node](https://github.com/Codeskop-io/codeskop-node) |
| Java and Kotlin (JVM) | `com.codeskop.sdk:codeskop-server` | [Docs](https://www.codeskop.com/docs/server/java?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) · [codeskop-jvm](https://github.com/Codeskop-io/codeskop-jvm) |
| PHP | `codeskop/codeskop-php` | [Docs](https://www.codeskop.com/docs/server/php?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) · [codeskop-php](https://github.com/Codeskop-io/codeskop-php) |
| Other languages | OpenTelemetry (beta) | [Docs](https://www.codeskop.com/docs/server/opentelemetry?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io) |

The web and server SDKs are open source under the MIT license.

## Metadata, not payloads

Our SDKs never capture request or response bodies, cookies or `Authorization` headers, and they drop query strings. The keys you ship in your apps can only send events, never read your data. [How the SDKs handle data](https://www.codeskop.com/docs/privacy?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io).

## Get started

1. [Create a free account](https://dashboard.codeskop.com/signup?utm_source=github&utm_medium=org_profile&utm_campaign=codeskop-io). Each project comes with a **Test** key and a **Live** key.
2. Add the SDK for your platform from the table above.
3. Trigger a test error and watch it arrive in your dashboard.

## Contact

Questions, feedback or a bug? Email **support@codeskop.com**, or open an issue in the SDK's repository.

[LinkedIn](https://www.linkedin.com/company/codeskop/) · [Instagram](https://www.instagram.com/codeskop.dev/) · [Read the launch post](https://dev.to/plinqdeveloper/launching-codeskop-crash-error-and-api-monitoring-for-mobile-web-and-backend-apps-3le6)

<sub>Built by Codeskop Ltd in Nairobi, Kenya.</sub>
