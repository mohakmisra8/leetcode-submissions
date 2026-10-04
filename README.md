# LeetCode Solutions — @mohakmisra8

> Submissions from [leetcode.com/u/mohakmisra](https://leetcode.com/u/mohakmisra/) · Repository: `leetcode-submissions`

---

## What is this?

This repository stores accepted LeetCode submissions for [@mohakmisra](https://leetcode.com/u/mohakmisra/). Layout and commit style match [neetcode-submissions](https://github.com/mohakmisra8/neetcode-submissions). Only solution code and the file name are stored. Problem statements are not copied.

---

## How submissions get onto GitHub

[neetcode-submissions](https://github.com/mohakmisra8/neetcode-submissions) is filled by NeetCode’s GitHub Sync at [neetcode.io/profile/github](https://neetcode.io/profile/github): connect GitHub once, then each submit, a bulk sync, or a manual sync from a problem’s history panel creates a commit.

LeetCode has no equivalent connect-GitHub page. This repo keeps the same end result:

1. **Save the accepted source** for a problem. Use the code from the submission, not the problem description.
2. **One file per submission**, under the topic folder and problem slug. The first file is `submission-0`.
3. **Commit on `main`** with `Add: <problem-slug> - submission-<n>`.
4. **First import** of solutions already accepted can be a single `Bulk sync: <count> submissions` commit, the same message NeetCode uses for a bulk sync.
5. **Push to `main`.** No session cookie, CSRF token, or access token is written to this repository.

After you solve a problem on LeetCode:

1. Open the accepted submission and copy your source.
2. Save it as `Data Structures & Algorithms/<problem-slug>/submission-<n>.<ext>`.
3. Commit `Add: <problem-slug> - submission-<n>` and push to `main`.

---

## Repository structure

```
<topic-folder>/
  <problem-id>/
    submission-0.<ext>   ← first submission
    submission-1.<ext>   ← second submission
    ...
```

**Example:**

```
Data Structures & Algorithms/two-sum/submission-0.java
Data Structures & Algorithms/binary-search/submission-0.py
```

---

## Supported languages

| Language | Extension |
|---|---|
| Python | `.py` |
| JavaScript | `.js` |
| TypeScript | `.ts` |
| Java | `.java` |
| C++ | `.cpp` |
| C# | `.cs` |
| Go | `.go` |
| Rust | `.rs` |
| Kotlin | `.kt` |
| Swift | `.swift` |
| SQL | `.sql` |

---

## Settings

NeetCode’s auto-commit, status filter, and bulk sync live at [neetcode.io/profile/github](https://neetcode.io/profile/github) and apply to `neetcode-submissions` only.

For this repo, the same choices are manual:

- **What to commit** — accepted submissions.
- **Where it goes** — `main` on `leetcode-submissions`.
- **History** — a new `submission-<n>` file for a new attempt. An edit to an existing attempt updates that file and uses the same `Add:` commit message style.
