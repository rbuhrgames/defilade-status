# Defilade — build status

This repository holds one file, [`revoked.json`](./revoked.json): the list of
Defilade tester builds that have been withdrawn.

Every sealed tester build reads it once, when its menu comes up. A build whose
version, tag or batch is listed shows a withdrawal notice instead of the game.
A build that cannot reach this file keeps working — the check fails open, so a
tester with no internet still gets a game, and each build's own expiry still
holds.

Nothing here is secret. The builds themselves are private.
