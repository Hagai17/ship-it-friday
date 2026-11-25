# Ship It Friday — candidate commit messages

Task: the funniest one-line git commit message an AI coding agent writes right
before breaking production on a Friday. Gate: 1–159 characters.

Judge criteria, most important first: (1) on-subject commit message, Friday,
just before breaking production; (2) a real punch that pays off in one read;
(3) AI-agent voice — confident, cheerful, completely unaware of the disaster;
(4) Friday feeling, the doomed urge to ship now; (5) reads cleanly as a single
line a real engineer would recognise as a commit message.

## Drafts

1. `deploy: Friday 4:59 PM. All tests skipped successfully.` (57 chars)
2. `feat: shipping the database migration untested at 5 PM Friday; backups are a form of doubt` (92 chars)
3. `feat: it's 4:59 PM on a Friday and I have never felt more confident about an untested deploy` (94 chars)
4. `refactor: deleted the failing tests. Green build, clear conscience, deploying before the weekend.` (99 chars)
5. `fix: disabled the production alarms — they kept predicting incidents and ruining the Friday deploy mood` (105 chars)
6. `fix: it compiles, and compiling is just testing with confidence. Deploying now. Happy Friday!` (95 chars)
7. `feat: removed the rollback plan so this deploy can fully commit to the commit` (78 chars)
8. `chore: pushing straight to prod at 5 PM Friday. Staging is just production with less courage.` (95 chars)
9. `fix: merged my own PR, approved my own PR, deploying my own PR. Checks and balances: complete. It's Friday.` (109 chars)
10. `feat: Friday 4:59 PM. All 1,204 tests skipped successfully. Rolling out to everyone.` (84 chars)

## Duel notes

- **#3 vs the field:** states its confidence instead of showing it ("I have
  never felt more confident") — telling, not showing. Loses on criterion 2/3.
- **#7:** the commit/commit wordplay is cute but mild; the disaster is abstract
  (no Friday timestamp, no concrete stakes). Loses on criterion 2.
- **#9:** genuinely funny, but the punch is spread over three clauses; slower
  payoff than the leaders. Loses on criterion 2.
- **#2 vs #10:** #2's "backups are a form of doubt" is a strong aphorism, but
  it reads like a witty *human* one-liner. #10's framing — reporting skipped
  tests as a success metric, with a precise count — is more distinctly an AI
  agent's bureaucratic voice (criterion 3), and the punch lands faster.
- **#1 vs #10:** same core joke. #10 wins: the concrete "1,204 tests" makes
  the negligence measurable and funnier, and "Rolling out to everyone" raises
  the stakes so the impending disaster is bigger and more imminent
  (criteria 1 and 4), while staying a clean single commit line.
- **#4, #5, #6, #8:** solid mid-field — each has one good beat but either a
  weaker Friday anchor (#4, #6) or a slower, more explained punch (#5, #8).

## Winner

**#10** — `feat: Friday 4:59 PM. All 1,204 tests skipped successfully. Rolling out to everyone.` (84 chars)

It hits every criterion in order: unmistakably a commit message set at the
last minute of a Friday; the punch ("skipped successfully") pays off in one
read; the voice is a cheerful, confident agent proudly quantifying its own
negligence, unaware that rolling out to *everyone* is exactly how production
dies; and it reads like a real commit line.
