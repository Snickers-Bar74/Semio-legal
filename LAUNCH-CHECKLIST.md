# Semio legal launch checklist

Prepared 28 October 2026. Local materials are prepared; release approval is open.
See [the shared checklist](../LAUNCH-CHECKLIST.md).

## Prepared

- Existing repository moved to `D:\Prosjekter\Legal\Semio-legal`; history/remotes and public base URL preserved.
- Public privacy policy retained and checked against `../../Semio/docs/PRIVACY.md`.
- Added support, data-deletion guidance and draft terms, linked from the home page.

## Data inventory and evidence

| Data | Where / purpose | Source to recheck for the release |
| --- | --- | --- |
| Progress, streaks, XP, settings, code, notes and review schedule | On device, lessons and practice; Android backup/transfer may include these | `Semio/docs/PRIVACY.md`, app backup rules |
| Optional usage counts and onboarding answers | PostHog EU, off until opt-in | App policy and analytics code |
| Crash details | Sentry when configured, separate from analytics choice | App policy and release configuration |
| Support mail | Mail provider, voluntary assistance | New support/deletion pages |

## Resolve before launch

- [ ] Confirm operator identity, address, monitored contact and full applicable privacy rights/complaint information.
- [ ] Set the intended audience and store age classification. Assess child-directed rules and whether child-friendly privacy wording or additional controls are needed.
- [ ] Confirm lawful bases, provider contracts, processing locations and transfer safeguards, including diagnostics and support email.
- [ ] Verify one-year analytics and 90-day diagnostic retention as stated; define support, provider log and backup handling.
- [ ] Test analytics opt-in/out, queue cancellation, diagnostics redaction and local deletion in the release. Confirm code/progress do not enter diagnostics.
- [ ] Verify offline narration, OS text-to-speech behavior, code sandbox and web-preview network restrictions against the policy.
- [ ] Reconcile any additional store SDKs or commercial model changes with the policy and terms. The current draft does not introduce a paid plan.
- [ ] Check lesson, narration, mascot, artwork, JavaScript naming and dependency rights. Preserve the existing proprietary license and third-party permissions.
- [ ] Review draft terms and set an effective date before publication as effective terms.
- [ ] Publish approved pages, test the HTTPS URLs and enter matching Play disclosures, then complete the shared checklist.

## Release record

Not yet launched or reviewed. Record app version, legal commit, URLs, date and reviewer here.
