## Why we publish authorship

Most projects hide machine authorship because authorship carries
stigma. We publish it because, here, authorship carries no blame — and
that is an old discipline, not an AI-era invention. Gerald Weinberg
called it *egoless programming* in 1971: the code is the team's, not
the author's, and review examines the work rather than the person. The
blameless postmortem tradition made the same move for incidents: asking
*who* destroys the information flow that prevents the next one; asking
*what the system allowed* improves the system.

We apply both to authorship. Code review accepts the **intent and
direction** of a change; once it is accepted, the change belongs to the
team. Accountability did not vanish — it moved. It attaches to the
merge, not the keystrokes: the human who accepts a change owns it. And
when an incident happens anyway, the postmortem asks what the system
allowed, not who — or what — typed it. Systems get better by iteration,
and iteration requires that honesty stays cheap.

There is a practical reason this matters more now: change volume. When
changes can be produced faster than any one person can type, per-change
ego has to go to zero or review turns adversarial. Reviewing intent and
direction scales. Reviewing keystrokes does not.

This is also why the disclosure above costs us nothing. Because
authorship assigns no blame, provenance is just data — useful for
auditing, useless for fault-finding. We can afford to show you exactly
who wrote what.

## Contributions

The same rules apply inbound. AI-assisted contributions are welcome;
disclose the assistance, and own what you submit — you are the human
accepting intent and direction before we ever see it. Your change gets
the same review as ours. Undisclosed machine-generated pull requests
that waste reviewer time are closed without ceremony; the problem is
never the tool, it is submitting work nobody stood behind.

## The short version

SFI is about ideas and building things. We never picked sides in the
operating-system or text-editor wars, and we are not enlisting in this
one (relevant xkcd: https://xkcd.com/378/). Tools change; review,
testing, and standing behind your work do not.

*Last updated 2026-10-27. Practices evolve; this document is versioned
with them.