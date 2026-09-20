# Creator-Publishing-Desk privacy notice

Document revision: 2026-09-20, lifecycle 2. This notice describes the
lifecycle-enabled CLI. The [app page](https://xellos216.github.io/app-info/creator-publishing-desk/)
distinguishes implementation, deployment and live-test status. The CLI identifies
these exact bundled document bytes by its SHA-256 policy version. The
[public notice](https://xellos216.github.io/app-info/creator-publishing-desk/privacy.html)
provides the same policy source text for comparison. Before authentication or API
use, the operator must read and explicitly accept this notice and the bundled
terms. Installing an update is not acceptance.

## Operator, service and purpose

Creator-Publishing-Desk is xellos216's personal, operator-controlled local CLI,
not a public hosted upload service. It uses YouTube API Services to deliver
selected productions to authorized channels and verify/recover those operations.
Google processes submitted data under its [Privacy Policy](https://policies.google.com/privacy).
The app is independent of Google/YouTube and does not claim audit approval.

## Data and storage

- Creator originals: selected videos, subtitles, thumbnails and authored settings;
  read and sent to Google only for authorized operations. They are not API cache.
- API data: returned channel/video/caption identity and operation observations,
  used for target checks, result verification and duplicate prevention.
- Credentials: desktop client settings, access/refresh tokens, granted scopes and
  expiry data. Google passwords are not collected by this CLI.
- Recovery checkpoints: resumable URLs and transfer/attachment/publication state,
  saved before uncertain remote mutations. These are private operational data.
- Operator records: plans, human approvals, policy acknowledgment versions/times,
  data-management requests and references. Some external reports/screenshots may
  contain API data and require separate classification.

Credentials and managed checkpoints reside in an owner-restricted local state
folder (0700 directory, 0600 files). The CLI does not encrypt storage at rest.
Originals and external reports remain in operator-selected folders. Explicitly
registered external paths and their file fingerprints are stored privately in
an inventory; there is no whole-disk or recursive backup search. Normal output
uses target identifiers rather than external paths, tokens or response bodies.
Administrators and tools authorized on this computer may access local files.

## Use, sharing and retention

Selected assets/settings and necessary authorization are sent to Google/YouTube.
The CLI has no advertising, data-sale or generalized model-training feature.
If an operator shares output with an AI assistant or another tool, that is an
additional disclosure; exclude credentials, original media and unnecessary
account information. This CLI does not send production files to the public
information website. The static site has no application login, advertising,
analytics scripts, cookies or browser-storage code. Hosting and GitHub issues are subject to
[GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

Ordinary stored API data is inventoried for refresh/removal within the applicable
30-day limit. A successful channel identity refresh updates only that profile's
API observation clock, not upload checkpoints or external evidence. Saved-state
writes do not renew API-data age. Legacy unknown ages remain urgent review items.
Credentials follow consent-related retention, not a blanket 30-day expiry.

There is no automatic service or timer. The operator must run the documented
daily review and authorized periodic validity/identity check, promptly handle
requests, and complete external cleanup manually. Listed files are the inventory
boundary; unregistered copies are always reported as uninspected. An operator-
attested external refresh is not described as an automatic API verification.
Filesystem deletion does not guarantee erasure from backups, snapshots or SSDs.

## Revocation and deletion

Access can be revoked in [Google permissions](https://myaccount.google.com/permissions).
That action does not erase local copies. The local disconnect command explicitly
acknowledges shared-project impact, requests revocation and clears managed
profiles/checkpoints only after confirmation. Uncertain revocation is reconciled
using the existing journal; it is not blindly repeated. External copies remain a
separate manual obligation. The operator must address the applicable seven-day
app-revocation/deletion-request or thirty-day Google-side-revocation duties as
soon as possible; these are maximum limits, not intentional waiting periods.

Offline deletion requests and cleanup previews do not require new policy consent.
Managed cleanup requires explicit execution of a reviewed target plan. It never
deletes original media, human approvals or external files. Unfinished recovery
requires explicit abandonment evidence before erasure. A local non-API history
barrier then requires separate review before a new upload, reducing blind-repeat
risk. A timeout, invalid grant or ordinary expiry never automatically deletes
credentials/checkpoints or proves when Google permission was revoked.

Deleting local data does not delete the video held by YouTube. Use YouTube Studio
or a separately authorized supported mechanism for remote deletion. This CLI
has no remote-video deletion command. Requests and local policy-consent receipts
are operator records, not authorization to retain embedded API copies forever.

## Questions and limitations

Contact [the public GitHub issue channel](https://github.com/xellos216/app-info/issues)
for privacy questions or deletion assistance without posting tokens, private
video links, media, email addresses or other private evidence. There is no
separate private intake service. The owner operates the local cleanup workflow.

The consent/data-lifecycle controls have offline mock-test evidence. Their
operation against the existing account has not been demonstrated. No automatic
schedule, real Google revocation, production eligibility or complete external
deletion is established by those tests. Deployment and actual operator agreement
must be checked separately from code availability.
