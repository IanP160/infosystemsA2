# Git Collaboration Practice

## Pair Information
- Student A: Ian Poonolly
- GitHub username: IanP160
- Student B: Dummy Person
- GitHub username: rzvorak

## Branch Work
- Feature branch created: `feature-about`
- What changed on the branch: Added two new bullet points to the About the Team section describing the team's client collaboration approach and focus on long-term value
- Who merged it into `main`: Student A (Ian Poonolly)

## Conflict Reflection
1. Why did the intentional conflict happen?
   Student A changed the decision heading and pushed it. Student B changed the exact same line locally before pulling that change, so when Student B tried to push, Git rejected it because the remote already had a different version of that line.

2. How did you resolve it?
   Student B pulled main, which triggered the conflict in index.html. VS Code showed both versions with conflict markers. Instead of just picking one side, we rewrote the line to a new heading that covers both ideas, deleted the conflict markers, staged the file, committed, and pushed.

3. Give two practices that can reduce unnecessary Git conflicts on a real team.
   - Pull before you start editing, not after.
   - Keep edits small and commit/push often instead of sitting on big changes.
