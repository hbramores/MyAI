# /build — Make one piece at a time

Inspect the project and choose the smallest safe, useful piece of the request. Build and test that one piece only.

Then stop and reply only with:

**Built:** [short description]
**Check:** [worked / needs attention]
**Paused for your review.**

Do not start the next piece until the user asks to continue. Do not show a long progress report, next-step preview, or file list. If one product decision blocks this piece, use the strict shared decision output contract instead.
