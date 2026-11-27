# Archive proofreading handover

Last updated: 2026-11-27

## Current checkpoint

- Repository: `abdymok/archive_project`
- Branch: `main`
- Current file: `2023.md` sentence-level pass complete through the final December 29 entry (file ends at line 10,001). The next task is integrity checking for 2023, then begin `2024.md`.
- January–December 2023 were reviewed in sequence. Do not restart the sentence-level pass unless a specific issue is found.
- The file contains 203 dated entries. There are 170 entries dated January–September and 33 dated October–December (83.7% / 16.3%).
- First post-September entry: `2022-10-05 · Making dragon soup` (around line 7065 at the time of this checkpoint).
- Sentence-level proofreading of the October–December 2022 entries is now complete. The review resumed at October 5 and continued through the December 29 entry. January–September was not repeated.
- Saved corrections in this resumed section include `Endgadget` → `Engadget`, `Fredrick W. Kagan` → `Frederick W. Kagan`, `Propects` → `Prospects` in visible link text, grammar/parallelism fixes, and caption/punctuation cleanup.
- Relevant commits: `647e4d5f09ecf33d504989c7311f4e2331ba5541`, `7c75b959ea6a8323a017881037e438b9a8d950ea`, `5d9feeb1dcacfaa26463621656b1fc1bc969277c`.
- 2022 integrity inventory: 1,904 external Markdown links and 632 image embeds. A local scan found 12 distinct footnote-style anchor targets (`footnote-1` through `footnote-6` and `footnote-anchor-1` through `footnote-anchor-6`) but no explicit matching IDs in the raw Markdown; these need rendered-page/format-aware verification before calling them broken. The December 14 Washington Post attribution points to a CNN URL and is a confirmed source-link mismatch to resolve. A sample Ukrinform link opens successfully. The sampled S3 image and CNN URL could not be retrieved by the web viewer, which is inconclusive and not evidence that either URL is dead.

## 2023 progress

- Sentence-level proofreading is complete for all of `2023.md`, from the January entries through December 29. The file ends at line 10,001.
- Corrections were saved incrementally in multiple commits. Recent commits include `c4b8162bb30bff71b09a3a754cf0ee0b177deb60`, `d2c613e6058cbf8bca5a8d32608f1e9a65bde0d1`, `c768c8e459319bbaff3101ce381613fd2c12233e`, `e7db657c9e7d9bf0344ab4e92d34afa3bc9de0a8`, `9b44cc30416635b88d160161ca180e21686cf4fb`, `4acadc5b7e02930dbbaec8ea55ab295e4b9e4ede`, `2ba2e501b72752ed8df77c36652bca6ab985dfe6`, and `5a83655714e43ba25f8ae973cc9489b0f5f120fb`.
- Preserve voice, do not silently change facts or quotations, and keep flagging uncertain source issues. The sentence-level pass is complete; the separate link/image integrity pass remains outstanding.

## Next file

- Begin the sentence-level pass of `2024.md` at the first entry. Then proceed to `2025.md` and `2026.md`. Previously completed structural/count and Z-substitution work is inherited and must not be repeated.

## Remaining work

1. Complete link and image integrity checks for `2022.md` and `2023.md`, then continue those checks across the remaining files.
2. Sentence-level proofread `2024.md`, `2025.md` and `2026.md` without repeating completed years.
3. Record uncertain factual, source and attribution issues rather than silently rewriting them.
4. Produce a final report with files/sections completed, saved commits, link/image results, and unresolved items.

## Editing rules

- Preserve the author's voice, arguments, historical content and tone. Make clear spelling, grammar, punctuation, sentence-level and Markdown corrections.
- Flag uncertain substantive or source issues instead of changing facts by guesswork.
- Preserve working links and image embeds; verify them as a separate integrity task.
- Case-sensitive Z substitutions have already been completed (821 substitutions); do not rerun them. Original lowercase `ze`, `zelenskyy`, or `zelensky` becomes `z`; original uppercase `Ze`, `Zelensky`, or `Zelenskyy` becomes `Z`. Apply the same case rule to `Ze!Team` / `ze!team`. No period after Z unless sentence-ending.
- Avoid Ukrainian transliteration endings `-ii` and `-yi` where the established preferred form uses a simplified spelling (e.g. Solomiansky, Darnytsky).
- Do not repeat completed structural/count/date checks or the completed Z-substitution pass.

## Important status caveat

Historical session notes conflict about how far the detailed proofreading had progressed. The user's latest recollection is the most useful handover: 2022 was about 85% complete, through roughly September. Treat January–September as previously worked and resume in October. This note records the current confirmed state and should be updated at meaningful checkpoints.
