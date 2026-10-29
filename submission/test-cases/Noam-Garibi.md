# Test Cases: Noam G

**Team group:** pressPlay()

<!--
HOW TO USE THIS FILE
1. Copy this file. Name the copy with your first name and last initial, like  maria-g.md
2. Leave TEMPLATE.md untouched for your teammates.
3. Write at least ONE failing test case. More is better.
4. Copy the block between the lines for each new test case.
5. Test IDs: use your initials plus a number, like  MG-01, MG-02. This keeps IDs unique across your team.
6. See docs/TESTING_FIELD_GUIDE.md for the sample test case TC-00.
-->

---

**Test ID**:NG-01
**Written by**: Noam Garibi
**Title**: The user can vote without being logged in
**Traces to:** REQ 02
**Test type:** Negative 
**Preconditions:** Not logged in and voted for a costume on the costume galary page. 
**Test data:**
The three costume options each incremented after clicking vote
**Steps:**
1. Get into the app
2. If logged in then logout
3. Vote on one of the costumes in the voting page

**Expected result:** An error message saying user is not logged and therefore they can't vote.
**Actual result:** The user is allowed to vote and the vote count goes up
**Status:** Fail 
**Severity:** Critical 
**V or V:** (Verification / Validation, Fail only)

---

**Test ID:** NG-02
**Written by:** Noam Garibi
**Title:** User can vote for their own costume
**Traces to:** REQ-10
**Test type:** Acceptance
**Preconditions:** Log in and submit a costume to be voted for.
**Test data:**
As a logged in user I created a costume and then voted for it. The number of votes incremented.  
**Steps:**
1. Create account
2. Submit costume to be voted for. 
3. Click vote on your own costume

**Expected result:** Error message telling the user they can't vote for their own costume. 
**Actual result:** The total votes for that costume gets incremented when it shouldn't be. 
**Status:** Fail
**Severity:** Major
**V or V:** N/A


**Test ID:** NG-03
**Written by:** Noam Garibi
**Title:** Costumes with plenty of votes don't appear on the leaderboard. 
**Traces to:**  REQ-14
**Test type:** Integration
**Preconditions:** There must be a created costume.
**Test data:**

Not all costumes show up on the leaderbaord

**Steps:**
1. login 
2. submit costume
3. check leaderboard

**Expected result:** It shows up on the leaderboard
**Actual result:** It doesn't always show up on the leaderboard
**Status:** Fail
**Severity:** Major



**V or V:**
**Test ID:**
**Written by:**
**Title:**
**Traces to:**
**Test type:**
**Preconditions:**
**Test data:**

**Steps:**
1.
2.
3.

**Expected result:**
**Actual result:**
**Status:**
**Severity:**
**V or V:**

---
