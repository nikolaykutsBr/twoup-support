# TwoUp — Support & Legal

Static support, terms and privacy pages for the [TwoUp](https://apps.apple.com/) iOS app,
hosted on GitHub Pages.

| Page | URL |
|---|---|
| Support | `https://nikolaykutsbr.github.io/twoup-support/` |
| Terms of Use | `https://nikolaykutsbr.github.io/twoup-support/terms.html` |
| Privacy Policy | `https://nikolaykutsbr.github.io/twoup-support/privacy-policy.html` |

The three pages are self-contained HTML with inline CSS in the app's own palette
(light and dark). `_style.inc` holds the shared style block used to generate them;
edit a page directly and it stays self-contained.

Written against the app's measured behaviour: no analytics or third-party SDKs,
no system permissions, no account or server, local-only SwiftData storage,
StoreKit purchases (yearly subscription + one-time), WKWebView for the web pane.
