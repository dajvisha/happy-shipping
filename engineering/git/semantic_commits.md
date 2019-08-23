# Semantic Commits

We have very precise rules over how our git commit messages can be formatted. This leads to more readable messages that are easy to follow when looking through the project history. But also, we use the git commit messages to generate the **Change Log**.

**Example:**
```
Fix[UserProfile]: Save only the month when selecting a date.
^--^^------------^ ^------------^
|   |               |
|   |               +--> Description in present tense and Capitalised.
|   |
|   +---------------> Scope (Optional)
|
+-------------------> Type: Feat, Fix, Chore, Docs, Revert, Refactor, Style, or Test. (Capitalised)
```

## Type
* **Feat:** A new feature
* **Fix:** A bug fix
* **Chore:** Other changes that don't modify src or test files
* **Docs:** Documentation only changes
* **Refactor:** A code change that neither fixes a bug nor adds a feature
* **Style:** Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
* **Test:** Adding missing tests or correcting existing tests
