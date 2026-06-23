# Business Logistics

We help small and mid-size businesses adopt AI for the parts of their operation that actually matter — sales, ops, marketing, and customer-facing work. Engagements range from a 2-week AI audit through full multi-agent system builds. Joshua handles engineering; Bradley handles delivery and business.

## What's here

This org holds active client engagements, internal product lines, and the engine that powers them. All repos are private. Counts at a glance:

| Category | Count |
|---|---|
| Client engagements | 3 |
| Internal product lines | 10 |
| Multi-agent orchestration engine | 1 |
| Shared libraries (on personal account, pending promotion) | 5 |

For engagement inquiries: [bradley@bl-az.com](mailto:bradley@bl-az.com).

## Conventions

(Visible to org members browsing internal repos.)

- `main` is honor-system protected; the local `.githooks/pre-push` hook in every repo blocks direct push to `main` and runs gitleaks before push lands.
- Every PR auto-requests review from `@Business-Logistics/leadership`.
- Every push triggers a server-side gitleaks workflow (`.github/workflows/secrets-scan.yml`).
- Each repo has a `STATUS.md` in its root for current state.
- For the full inventory by category: `gh repo list Business-Logistics --topic <product|client|engine>`.

## Activating hooks on a fresh clone

```bash
bash .githooks/install.sh    # configures core.hooksPath; one-time per clone
brew install gitleaks        # if not already installed
```
