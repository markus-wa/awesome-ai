# AGENTS.md — working in this repo

This is a **hand-curated** collection of AI-coding references. It is a reading list,
not an index. Curation is the whole product: a wrong or unasked-for link costs more
here than a missing one gains.

## Hard rules

1. **Never add a link the user did not ask for.** Propose candidates in chat and wait
   for a yes. No "I found this while browsing", no bulk imports, no scripts that
   discover and commit links.
2. **One entry = exact URL + source + a few words on why**, in plain language, in the
   user's voice. No more than a line; the README is for deciding what to read, not a
   summary of it.
3. **Stay rough.** The file is a pointer list for not losing references. Do not add
   annotations, expanded descriptions, per-entry sections or "context" paragraphs, and
   do not grow an existing entry's line while touching it.
4. **Verify before adding.** Check the URL resolves and that it is the *primary*
   source. No aggregator, mirror, search-result or tracking URLs.
5. **Never argue popularity.** Star counts, view counts and "widely recommended" are
   not reasons to include something.
6. **Unconfirmed candidates keep a `?`** and stay marked until the user confirms,
   edits or deletes them. Do not quietly promote a candidate to confirmed.
7. **Keep diffs additive.** Do not restructure sections, reflow entries or reformat
   the file while adding something. Removing or renaming an entry is the user's call —
   ask.
8. **No scaffolding** — no badges, TOC, license, CI, link-checker scripts or tooling
   unless explicitly requested.

## Section vocabulary

Grouped by *kind*, then attributed to a source inside the entry:

`stack` · `skills` · `talks` · `writing` · `courses` · `repos & tools`

A new section is a decision, not a detail — ask before inventing one.

## Verification

`curl -sI <url>` is enough for a status code. When a title or URL cannot be pinned
down, say so instead of guessing: write `?` plus what is known, and leave the URL out
if there is none.
