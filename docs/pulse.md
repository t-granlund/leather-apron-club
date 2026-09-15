# The Pulse — how the club hears its own heartbeat

> The grove learns because its owners teach it. This document is the law
> for how that teaching is shared: **selectively, securely, and never
> without the owner's hand on the lever.**

## The loop, in one paragraph

Each business workspace carries a private pulse directory. Once a week —
or whenever the owner feels like it — the grove drafts a pulse entry from
the actual work done (jobs quoted, reviews answered, hours saved). The
owner edits it down to what they are WILLING to share, marks each line
private or shareable, and commits it. The commit goes to a private club
repository that only members can read. The steward (T. Granlund) curates
a monthly digest for the council table: patterns, needs, wins worth
copying. Nothing becomes public that was not marked public by a human.

## The directory

- Every business workspace: `.spruce_grove/pulse/` (git-ignored in the
  business's own repo if it has one — the pulse travels to the CLUB, not
  to the world).
- The club collection: a **private** repository,
  `t-granlund/leather-apron-pulse` (to be created; members granted read).
- The council table sees the curated digest. The public site sees only
  aggregate, anonymized patterns, and only when the steward decides the
  pattern teaches without exposing.

## The entry format

One file per week per business: `pulse-YYYY-WW.md`. Front-matter is
machine-readable so the digest (and, later, a real database) can chew it:

```
---
week: 2026-W38
business: The Lock Doctors
hours_saved: 3.5          # the owner's honest estimate
shared: true              # false = stewards see it exists, nothing else
---

## Wins
- Automated the review replies: 11 answered, ~90 minutes saved.

## Needs
- A better way to quote multi-door commercial jobs.

## A thing other shops should steal
- The no-show follow-up texts cut no-shows roughly in half this month.

## Private notes (shared: false sections stay on this machine)
- [the owner writes what stays home here]
```

## The three laws

1. **The owner's hand commits.** The grove drafts; the owner decides.
   No automated push ever leaves a business workspace without a human
   running the command.
2. **Private is the default.** `shared: false` is the safe state. The
   public surfaces of the club never name a member's numbers.
3. **Value flows back.** A member who shares gets the digest: what the
   other shops learned this month. The pulse is a trade, not a tax.

## Where it goes

The digest feeds Friday councils (the "what did we learn" beat). The
accumulated, consented patterns become the club's teaching material when
the Junto model plants in the next market — the Apple-alumni network is
the seed list, NWA is the proof. Each new city gets the same machine,
the same laws, and a pulse of its own.
