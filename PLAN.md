# homebrew-tap: what is left to build, in order

The README banner is in flight in PR `#1`. A `site/` one-pager is not
applicable: the tap only delivers apps, and each app's site belongs in its
own repository. What is left is any check at all.

### Phase 1: the checks, one command, on every PR

- [ ] `plans/01-quality-gates.md` - brew style and audit as one script,
  the shared security gate, and install proofs on macOS and Linux.
