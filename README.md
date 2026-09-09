# mettle-privacy

Three redirects, and nothing else.

This repo was Mettle's privacy policy, support page and account deletion page,
served by GitHub Pages from 2026-07-17. On **2026-09-09** all three moved to
[walkmettle.com](https://walkmettle.com) — the domain the app's invite links
already run on — and live in the
[walkmettle](https://github.com/danielchungf/walkmettle) repo now.

| Old | New |
|---|---|
| `danielchungf.github.io/mettle-privacy/` | walkmettle.com/privacy |
| `.../support.html` | walkmettle.com/support |
| `.../delete-account.html` | walkmettle.com/delete-account |

**Do not delete this repo, and do not turn Pages off.** The old address is
compiled into every build of the app already on a phone — the sign-in screen's
legal line and the `privacyPolicyURL` / `PRIVACY_POLICY` constants — so those
links keep arriving here for as long as those builds are installed. The store
listings point at the new URLs.

GitHub Pages cannot serve a 301, so each page is a meta refresh plus a
canonical link plus a script plus a visible link, in that order of preference.

The policy's source of truth is `docs/PRIVACY_POLICY.md` in the app repo.
Nothing here is maintained.
