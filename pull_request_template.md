# PR Background and Summary
*Provide a brief background summary or ticket with more information*

# Testing
*Provide information on how this change was tested (e.g. unit tests, tested on synthetic data, deployed and clicked through on Dev, etc)*

# Screenshots/Video
*Provide screenshots or a video with more detail if it helps reviewers with context*  

# Expected Review Time
*Provide the expected time for review and justification for this time*

# Resolves Jira Task

[CB-]("https://hn-company.atlassian.net/browse/CB-")

# PR Writer's Final Checks

- [ ] Do all the unit tests pass?
- [ ] Does this PR affect the unit tests of any other module?
- [ ] Do you need to include a Loom video?
- [ ] Have you included an expected review time?
- [ ] Have you checked for SonarCloud issues?
- [ ] Does any documentation need to be written or updated in Notion?
- [ ] Take a well-earned break, stretch! 🥳

# Checklist for Reviewer
*Add PR-specific checks to this list*
- [ ] Check for the formatting of the module:
    - [ ] Are the docstrings sufficient?
    - [ ] Are the variable names clear to understand and include typehints?
    - [ ] Is the code easy to follow?
- [ ] Are the functions single responsibility?
- [ ] Are there SonarCloud issues?
- [ ] Do the unit tests handle all expected situations?
    - [ ] Do they consider nulls?
    - [ ] Missing columns?
    - [ ] Edge cases?
- [ ] Is there Notion documentation, if beneficial?
