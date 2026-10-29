# Release workflow

The private/local working repository is maintained separately from this public checkout. Unapproved drafts and personal review notes stay there.

1. Review the complete story, cover, comic, captions, social copy, source scope, and desktop/mobile layout.
2. Integrate author notes and re-run checks and PDF rendering.
3. Record author approval and the exact package hash in the working repository.
4. Prepare only that approved package into `posts/<issue-slug>/` here.
5. Inspect `git diff --cached` and commit the individual release.
6. Push only when that story is authorized for release. Posting to LinkedIn/Facebook remains a separate action.

This repository contains no Actions workflow, Pages configuration, DNS file, or automatic posting.
