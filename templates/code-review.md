<!-- tags: review, coding, github -->

# Code Review

## PR
<!-- Link to the PR -->

## Review Focus
<!-- What should the reviewer pay extra attention to? -->

-

## Review Checklist
<!-- Check each area -->

### Correctness
- [ ] Logic is sound and handles edge cases
- [ ] Error states are handled
- [ ] No obvious bugs

### Design
- [ ] Code is well-organized and follows existing patterns
- [ ] No unnecessary coupling
- [ ] Appropriate abstractions (not over-engineered)

### Security
- [ ] No exposed secrets or keys
- [ ] Input is validated/sanitized
- [ ] Auth/authz checks are in place where needed

### Performance
- [ ] No N+1 queries
- [ ] No unnecessary loops or blocking calls
- [ ] Reasonable resource usage

### Maintainability
- [ ] Code is readable and self-documenting
- [ ] Comments explain _why_, not _what_
- [ ] No dead code or debug logging left in
- [ ] Tests cover the change

## Verdict
<!-- Pick one -->

- [ ] Approve
- [ ] Approve with suggestions
- [ ] Request changes (see comments)
