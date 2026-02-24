<!-- 
================================================================================
Pull Request Template
================================================================================
This template ensures all PRs contain necessary information for review and 
tracking. Please fill out all sections marked with [brackets].

IMPORTANT: 
- Link this PR to an issue using "Fixes #123" or "Closes #123"
- Check all applicable items in the Definition of Done
- Mark optional items with strikethrough (~item~) if not applicable
================================================================================
-->

## Pull Request Information

<!-- Basic information about this pull request -->

**Internal ID:** [Internal tracking ID]  
**Private Issue:** Fixes #[issue number]  
**Public Issue:** Fixes #[issue number]  


**Summary:**
<!-- Briefly describe what this PR changes and why -->

---

## Branch Protection Requirements

<!-- These are repository requirements that are automatically enforced -->
- [x] Require PR
- [x] Require review
- [x] Require linked issue

---

## Definition of Done Checklist

<!-- 
Mark completed items with [x]
Mark optional/not applicable items with strikethrough: ~- [ ] Optional item~
Optional items are excluded from completion rate calculation
-->

### Requirements
<!-- Business and functional requirements -->
- [ ] All acceptance criteria are fulfilled and tested
- [ ] All related tasks are set to done

### Code Quality
<!-- Standards and conventions that ensure maintainable code -->
- [ ] Coding Guidelines followed (Naming Convention, design principles)
- [ ] No compiler warnings or errors
- [ ] No code analysis warnings (ReSharper, StyleCop, FxCop, TSLint)
- [ ] UI controls have unique automationID (if applicable)

### Testing
<!-- Verification that changes work as expected -->
- [ ] Unit tests and integration tests written
- [ ] All tests pass successfully
- [ ] Build server passes

### Review & Documentation
<!-- Knowledge sharing and documentation -->
- [ ] Documentation updated (code comments, wiki, README if needed)

---

## Additional Notes

<!-- 
Optional: Add any additional context reviewers should know:
- Specific areas to focus review on
- Implementation decisions and trade-offs
- Dependencies or breaking changes
- Screenshots (for UI changes)
- Performance considerations
-->
