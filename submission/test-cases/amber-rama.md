**Test ID:** 01-AR
**Written by:** Amber Rama
**Title:** User cannot cast a fourth vote after using all three votes
**Traces to:** REQ-09, REQ-12, UML_SEQUENCE.md
**Test type:** Boundary Value
**Preconditions:** Log in as `amberama` with password `12345678`. Reset the demo data first.
**Test data:** Three different costumes, followed by an attempt to cast a fourth vote.

**Steps:**
1. Open the Vote page.
2. Vote for `A Very Polite Ghost`.
3. Vote for `Vampire Accountant`.
4. Vote for `Zombie Barista`.
5. Observe the votes remaining count.
6. Click Vote on any available costume one more time.

**Expected result:** After the third vote, the app displays `Votes remaining: 0`. The fourth vote is rejected, the vote count does not increase, and the remaining vote count stays at 0.

**Actual result:** The fourth vote is accepted, and the app displays `Votes remaining: -1`.

**Status:** Fail
**Severity:** Major
**V or V:** Verification

