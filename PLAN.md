# homebrew-tap: what is left to build, in order

The README has its banner (PR `#1`). A `site/` one-pager is not
applicable: the tap only delivers apps, and each app's site belongs in its
own repository. Each plan below is built phase by phase and ticked here
when all its boxes are.

### Phase 1: the checks, one command, on every PR

- [ ] `plans/01-quality-gates.md` - brew style and audit as one script,
  the shared security gate, and install proofs on macOS and Linux.

### Phase 2: repository hygiene

- [x] `plans/02-repo-hygiene.md` - a security policy and GitHub topics.
