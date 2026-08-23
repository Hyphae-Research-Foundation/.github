# Review standard

Review decides whether a change is worth including and whether its known risks
are acceptably controlled.

Reviewers read the approved issue first, verify scope, correctness, safety,
compatibility, evidence, maintainability, rights, and documentation, and
distinguish blocking requirements from non-blocking preferences.

Normal changes require one approving human maintainer other than the author.
Critical and materially AI-assisted changes require two approving human
maintainers, including an accountable area owner when named, plus a 72-hour
public review window after the latest substantive commit.

Automated approval does not count. Authors cannot approve or merge their own
work. CI and DCO must pass on the exact selected commit, conversations must be
resolved, and substantive pushes invalidate prior approvals.

Project repositories define their critical areas and may add stricter gates.
