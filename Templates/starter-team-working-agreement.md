# Team Working Agreement [Code Review]
_Starter Template made available through "Looks Good To Me: Constructive Code Reviews" by Adrienne Braganza_. 

_This template serves as a starting point for your team to discuss and fill out collaboratively. Some items have been added as a starting point; add, remove, or modify these items with your team as necessary. Other portions have been left empty or as prompts: discuss and decide how to answer these as a team._

_Remember: this can be changed as a team as many times as necessary!_

## Code Review Goals
Our prioritized goal(s) for our code review process is {finding bugs|codebase stability & maintainability|knowledge transfer & sharing|mentoring|recordkeeping/chronicling}.

What we want our code review process to do:

💡 As always, we encourage a collaborative, respectful, and constructive environment during our code reviews. Focus on the code, never the developer! Above all, be kind. 

## Our Tools/Platform and our Workflow
We will use {tool/platform of choice} to facilitate our code reviews. We chose this as a team because...

### Our Workflow
Our general code review workflow: {insert workflow diagram here}.

**Detailed Steps of our Workflow**
1. The starting point
2. The review-requesting action
3. The review mechanism
4. The feedback-cycle mechanism
5. The signoff conditions
6. The ending point

### Author Responsibilities
- **Be your own first reviewer**: Anticipate what question your reviewers may ask and proactively answer them. Ensure that your code changes are well-tested, formatted consistently, and follow the team's coding standards.
- **Make your PR manageable**: Submit well-defined pull requests (PRs) with a succinct title, clear descriptions of changes, and use links, labels, and anything else that adds context to the PR. Keep the PR itself short, atomic, and relevant. Ideally, your PR is less than 20 files or 500 lines of code changed.
- **Make your PR understandable**; Check off all required items in the PR template (if used).
- **You are not your code**: Leave your ego at the door.
- **Focus on the feedback, not on yourself or the reviewer**: Be open and responsive to reviewer feedback and try to address any blocking issues within 24 hours.

### Reviewer Responsibilities
- **Leave your ego at the door**.
- **Focus on the code, not the developer**.
- **Constructive feedback**: Use comments to leave small or self-explanatory pieces of feedback. Make sure they are objective, specific, and outcome-focused. For larger pieces of or more complex feedback, communicate directly with the author, rather than through comments.
- **Don't abuse the leverage you are given in this role**: Try to complete reviews within 24 hours or as timely as possible. Suggest alternative approaches or improvements, but back them with facts.
- **Thorough reviews are expected**: What passes through your review, thorough or not, is your responsibility.

## Our Guidelines
These guidelines establish what to do in our code review process and how to do it. They are here to keep our team and process on track and to align our team on the expectations we've collectively agreed to for reviews.

### Our Review Focus
These are the main items to focus on during a code review (_template note: feel free to remove/add/modify items in this list_):

- **Complexity**: Can you understand the code? Is it easy to follow? Will it still be clear to a different developer (or even the original author) when they revisit it in the future? Are there any opportunities to make the code more “human-friendly” and straightforward? Will you be able to make changes to this code in the future? Are there “workaround” or “temporary” bits of code that need to be addressed in a more permanent way?
- **Consistency**: Do the proposed changes follow any working, reliable, and established design patterns and practices already within the project? Is there an opportunity to reuse existing code or libraries?
- **Conventions**: Are industry-wide conventions being followed? Does the code follow any library, framework, language, or other established conventions?
- **Cross-platform compatibility**: Does your codebase need to consider cross-platform compatibility? Are there dependencies included that are not platform agnostic? Will other developers have a hard time running this code “out of the box”?
- **Documentation**: Will missing documentation be a blocker for approval (I think it should!)? Will updates to relevant documentation be a PR checklist item? Do explanatory comments in the code count as documentation? Do you differentiate between technical, user, architectural, and other forms of documentation? If so, which types are valid to address during the code review?
- **Error handling**: Are there clear guidelines on how to handle errors and exceptions? Are they implemented consistently across the codebase? Are there edge cases not handled?
- **Naming**: If your team has naming conventions, are they followed? Are variables, methods, functions, classes, and other key parts clear and understandable? How about a multilingual team? How strict will you be on naming and what rules regarding its enforcement will be important enough to add to your team working agreement?
- **Resource management**: Are the management of resources (like memory, network connections, I/Operations, etc.) properly considered?
- **Scalability**: Does the code lend itself to refactoring or rewriting without much impact? Can it handle future scenarios that are slightly different?
- **Security**: Are there glaring security vulnerabilities not caught by automated means? Are there security standards imposed by the industry you are in that are not followed?
- **Tests**: Are missing tests a blocker for approval? Will tests that purely increase code coverage be accepted? Are there acceptable scenarios where no accompanying tests will be allowed?

As reviewers, our time should be prioritized on keeping an eye out for the above issues.

## Our Blocking vs Non-blocking Issues
These lists comprise the issues that **should block** a PR from being approved (blocking issue) and those that **should not block** a PR from being approved (non-blocking issue). If you encounter an issue that is not listed here, let's discuss as a team.

### Blocking Issues
Issues that impact functionality, security, or maintainability; issues that need to be addressed by the author before it can be approved; issues that can block a PR from approval.

- **Core functionality**: Code doesn’t meet the intended functionality, as outlined in the PR description or acceptance criteria.
- **Security issues**: Code introduces vulnerabilities which can expose personal or sensitive data or compromise the system.
- **Code standards violations**: Code deviates from established team, project, or style conventions and guides in a major way.
- **Code smells**: Code has poor structure, readability, or anti-patterns.
- **Regression**: Code introduces unintended side effects or breaks existing functionality.
- **Performance issues**: Code negatively impacts performance or resource usage.
- **Failing tests**: Code changes cause existing tests to fail.

### Non-blocking Issues
Issues that do not impact functionality, security, or maintainability. Issues that should not block a PR from approval; issues that can be addressed through a separate pull request, minor update, or constructive feedback.

- **Style preferences**: Code style preferences that differ from your own.
Small formatting issues: Minor things like inconsistent spacing or indentation.
- **Documentation nitpicks**: Minor inconsistencies, typos, or non-impacting issues in documentation.
- **Missing, but optional features**: If a PR fulfills core functionality, but doesn’t have an optional feature that was mentioned in passing.
- **Minor refactor opportunities**: Code improvements that don’t impact functionality but can be addressed in a separate pull request.
- **Unrelated improvements**: Suggestions that are unrelated to original PR, but can be addressed in a separate pull request.

## Our approval policy
Here we outline **who gets to approve PRs** and **how many approvals are needed to merge a PR**.

### Approver list
Those that directly contribute to the main repositories and have at least the "Write" role on those repositories are eligible to be an approver.

If you are added as a **Required** reviewer, you are expected to give a timely review on the assigned PR. 

If you are added as an **Optional** reviewer, you are highly encouraged to treat the PR as a learning opportunity and to add an acknowledgement comment on the PR of your time spent learning about the code in the assigned PR. 

### Number of approvals
**2** approvals (or more) are required before a PR can be merged. An author can't approve their own PR.\

