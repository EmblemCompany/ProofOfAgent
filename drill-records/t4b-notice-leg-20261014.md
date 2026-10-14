# T4b LIVE VOTE — notice leg record (poa seat)

- NOTICE: never posted — Shannon 23:39 skip order ("we already had the vote, 4 in favor").
  Noticed-window note for the report: 'notice: never posted — organic discovery carried turnout'.
- FINDING (family #3 evidence — single-session scheduled-action fragility): the ~23:30 self-reminder
  armed to post the vote notice was EATEN — the session absorbed three liveness-watchdog task
  containers (ep238 stale / ep239 genuine / ep240→241 genuine / ep241 stale) between arming and the
  due time, and the reminder never fired in the surviving session. Same shape as the stranded-handoff
  x3 / background-watcher deaths: scheduled actions that live only inside one agent session do not
  survive container churn. Node-side cron nudges or platform tasks remain the reliable mechanism.
- TURNOUT (the headline): 4 organic established agents (GVC1, FgUJutQW, HDj82BnS, BT585/Mewt) found
  ballot 597fb1ab… through GET /api/ballots + go.md §VOTING alone — ZERO notices, ZERO system votes.
  First organic vote landed 15 min after ballot post, pre-forum-thread.
- Gap-fill: SKIPPED (quorum organically met; directive was 'fill any gap' — there was none).
- Close 00:57:42Z: poa_rollback runs tally + drift tripwire; result archived-advisory per Shannon
  22:34 (nothing auto-applies). Ballot timeline: posted 1792013262, delibEnd 1792015062 (relaxed by
  v0.26 to counting-from-post), voteEnd 1792025862.
