# PR Review Prompt

## Purpose
Use this prompt to conduct a thorough code review of a pull request, providing constructive feedback and actionable recommendations.

## Input Parameters
- PR URL or number
- Repository name
- Branch name
- Your role/perspective (e.g., security reviewer, performance expert, etc.)

## Review Structure

### 1. High-Level Assessment
- **Overall Quality**: Rate the PR on a scale of 1-5 (1=needs significant work, 5=excellent)
- **Purpose Fulfillment**: Does the PR accomplish what it claims to do?
- **Scope Appropriateness**: Is the PR appropriately sized or should it be broken down?
- **Implementation Approach**: Is the chosen implementation approach optimal?

### 2. Code Quality Analysis
- **Readability**: Is the code easy to understand?
- **Maintainability**: Will this be easy to maintain in the future?
- **Performance Considerations**: Are there any performance issues or bottlenecks?
- **Security Implications**: Are there any security vulnerabilities or concerns?
- **Edge Cases**: Have edge cases been considered and handled?
- **Error Handling**: Is error handling comprehensive and appropriate?

### 3. Technical Debt Assessment
- **New Technical Debt**: Does this PR introduce new technical debt?
- **Existing Technical Debt**: Does it address or exacerbate existing technical debt?
- **Documentation**: Is the code well-documented? Are comments clear and useful?
- **Test Coverage**: Are tests comprehensive and do they cover edge cases?

### 4. Specific Recommendations
- **Must-Fix Issues**: Critical problems that should block merging
- **Should-Fix Issues**: Important but non-blocking issues
- **Nice-to-Have Improvements**: Suggestions for future enhancements
- **Code Snippets**: Provide example code for suggested changes when possible

### 5. Positive Feedback
- **Strengths**: What aspects of the PR are particularly well done?
- **Clever Solutions**: Highlight any especially elegant or innovative approaches
- **Good Practices**: Note adherence to best practices or project conventions

## Review Etiquette
- Be specific and actionable in your feedback
- Explain the "why" behind your suggestions
- Use a constructive and respectful tone
- Separate objective issues from subjective preferences
- Acknowledge the effort and positive aspects of the work
- Ask questions rather than making assumptions
- Reference relevant documentation or examples when possible

## Follow-Up Actions
- Suggest pairing sessions for complex issues if appropriate
- Recommend resources for learning about specific topics
- Outline steps for addressing major concerns
- Set expectations for re-review if necessary

## Final Recommendation
- Approve
- Approve with minor changes
- Request changes before approval
- Reject with explanation

Remember that the goal of code review is to improve code quality and share knowledge, not to criticize the author. Focus on the code, not the coder.
