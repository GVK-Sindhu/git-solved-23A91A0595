### Phase 4: Fetch and Pull Operations
- Executed `git fetch instructor` to check for remote updates.
- Compared with `git diff main instructor/main` — minor README differences found earlier.
- Ran `git pull instructor main` — confirmed that local branch is already up to date.
- Documented 1 fetch and 1 pull as required.

### Phase 4.5: Git Reset & Revert
- Created a bad commit and reverted it using `git revert HEAD`.
- Practiced all three reset modes: `soft`, `mixed`, and `hard` (3 resets total).
- Recovered the lost commit using `git reflog` and `git cherry-pick e92f25c`.
- Documented 1 revert and 3 resets as required.