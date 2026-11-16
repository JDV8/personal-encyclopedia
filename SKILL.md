---
name: personal-encyclopedia-topic
description: >-
  Use when the user names a topic to add to their personal encyclopedia repo (a
  markdown knowledge base taught from first principles), or asks to expand or
  restructure an existing topic there.
---
# Adding a topic to a personal encyclopedia

A personal encyclopedia is a git repo of markdown courses on topics the user names. The goal is understanding built from first principles, not a direct explanation. If the user says "internal combustion engine", don't open with how an engine works. Teach the concepts underneath it (energy, heat, pressure and volume, combustion chemistry, the thermodynamic cycles, mechanisms), and let the engine emerge at the end.

The repo location comes from memory or from the user. Typically it's a private repo on their personal GitHub, cloned on the box.

## A. Understand the request
1. Identify the topic and what the user really wants to understand: the mechanism, the history, the stories, the practice.
2. Decide which disciplines it rests on, and list the prerequisite concepts in dependency order, from most fundamental to the topic itself.
3. If the scope is truly ambiguous, for example a word with several fields, ask one short question. Otherwise decide and proceed.

## B. Place it in the tree
4. Put content in a nested discipline tree. The thing asked about is usually NOT at the top level. For example: `engineering/mechanical/thermodynamics/heat-engines/internal-combustion-engine/`, `philosophy/history/ancient/greek/`, `religion/abrahamic/christianity/bible/`.
5. Reuse existing branches where they fit. Create sibling branches instead of forcing a topic under the wrong parent; for example, religion is a sibling of philosophy, not a child. Cross-link related branches.
6. Name folders and files in kebab-case. Number lessons in reading order (`01-…md`, `02-…md`), and number subfolders when their order matters.

## C. Write thoroughly
7. Err heavily toward thoroughness. Use many granular files rather than a few broad ones. Split any lesson that covers more than one big idea.
8. For a body of works or people, give each its own overview file. Examples: every book of a scripture, every major thinker, every key primary text, every major component or subsystem.
9. Add a `glossary/` folder for the branch, with a README table of contents and many entries (aim for 100 to 150+ for a big subject). Each entry is a real paragraph with cross-links.
10. Each lesson file has:
    - **Prerequisites**: links to what to read first
    - The body, roughly 500 to 1200 words, built up from the basics
    - **Key ideas**: a short recap
    - **Where this leads**: links to the next lessons and to related branches
   Overview files (a book, a thinker, a text) can use their own structure: name and meaning, dating and authorship (traditional vs scholarly), context, an outline, key passages or ideas, themes, connections and reception.
11. Stay accurate and neutral. Where traditions or scholars disagree, present each view fairly. Never invent quotes, dates, citations or books.

## D. Folder conventions (required in every folder)
12. **The first file is `README.md` and it is a table of contents.** It gives a one-paragraph overview, a suggested reading order, and a complete linked list of every file and subfolder inside, with each subfolder's contents listed one level deep.
13. **References.** End every folder's README with `## References & further reading`. Recommend only real, well-known books: primary sources with recommended translations, accessible introductions, and deeper scholarly works. Tag each as Beginner, Intermediate or Advanced, with a one-line reason. If you're unsure a book exists, leave it out.
14. Keep the root `README.md` map current: the top-level branches and the newest additions.

## E. Verify and publish
15. Script a link check so that every relative markdown link resolves. Fix every broken link.
16. Check that every folder has a README with a TOC listing all of its children, plus a references section.
17. Commit in logical chunks, one per branch or section, with clear messages, and push to `main` as you go so progress isn't lost.

## F. Report to the user
18. Send the repo link, a short tree of the new or changed branch (3 to 5 levels deep), the file and word counts, and one or two suggested next topics or expansions. Keep the message short: the repo is the deliverable, not the chat.

## Large requests
For a big subject (for example a whole scripture or a whole tradition), work in passes. Do the skeleton and READMEs first, then the foundation lessons, then the per-item overviews, then the glossary and references, committing after each pass.
