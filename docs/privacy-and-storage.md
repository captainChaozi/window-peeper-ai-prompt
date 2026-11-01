# Window Peeper AI: privacy and storage summary

Table form of the [privacy policy](https://windowpeeperai.pro/privacy-policy) for [windowpeeperai.pro](https://windowpeeperai.pro/) (policy dated 2026-10-23, read 2026-11-01).

| Item | How it is handled |
|---|---|
| Photo before upload | Browser resizes it and removes EXIF metadata; a selected file stays on your device until a signed-in request |
| Storage | Inputs and generated files in a **private** Cloudflare R2 bucket |
| Generation provider | APIMart, with temporary access to the needed inputs; its own terms apply |
| Input cleanup | Scheduled after the task finishes (period shown on the homepage); kept while an unresolved task is investigated |
| Provider portrait assets | Scheduled for deletion when processing ends; failed cleanup is retried |
| Paid videos | No automatic expiry; download or delete from your account |
| Account deletion | Removes associated media; cleanup is retried if it fails |
| Image previews | Disabled in this release |
| Public sharing / gallery | Disabled; videos private by default |
| Payment cards | Full card details not received; payment providers process checkout |
| Cookies | Necessary only by default; analytics, ads and third-party chat off until consent; remembered 180 days |
| External reference videos | Loaded from other hosts by your browser; your portrait is not sent to them |

## Caveats stated by the policy

- Deleting the service's copies does not establish deletion of every provider copy.
- Provider documents do not establish that a particular cleanup request has completed.

Related: [task-status.md](task-status.md), [editorial-method.md](editorial-method.md).

Maintained by Chaozi, developer of Window Peeper AI (independent; not affiliated with any platform, brand, performer or template creator).
