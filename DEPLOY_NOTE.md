# Public Pages Deploy Note

This folder is the publishable static site output.

Recommended setup:

1. Keep the main strategy repository private.
2. Create a second public repository only for the static dashboard.
3. Copy the contents of this folder into the public repository root.
4. Enable GitHub Pages for that public repository.

Automation helper:

- `scripts/publish_review_dashboard_pages.ps1`

Default expectation:

- The public repository is cloned next to this workspace.
- Local path example:
  - `F:\cursor\yunqi-daily-review-pages`

Before publishing each day:

1. Refresh review data.
2. Rebuild the report.
3. Rebuild this dashboard.
4. Run the publish script.
