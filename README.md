# Personal encyclopedia

A private collection of notes and short courses on topics of interest. It is organized as a discipline tree: folders of markdown files, nested the way a field is actually built, not the way a casual question is usually asked.

## First-principles approach

When a topic is added here, the goal is not to jump straight to a finished explanation of that topic. The goal is to teach the underlying concepts that make the topic intelligible.

If the question is "how does an internal combustion engine work?", the path should run through something like `engineering/mechanical/thermodynamics/` (heat, work, cycles, combustion) before the engine itself appears. The thing asked about usually sits lower in the tree, after its prerequisites, not at the top level.

This does two things. It keeps the library honest about dependence: you cannot really understand an engine without heat and work, or Aristotle without the problem of change, or the Gospels without Second Temple Judaism. It also means later topics can reuse earlier ones instead of repeating them.

## How this encyclopedia is built

The process for adding or expanding a topic — first principles, where to nest it, how thorough to be, glossary and table-of-contents rules, and how to publish — is in [SKILL.md](SKILL.md).

## Folder conventions

- **Nest by discipline.** Place a subject under the broader field it belongs to. Resist putting a proper name or a gadget at the root just because that was the prompt.
- **Every folder has a `README.md`.** That file says what the folder is, lists prerequisites (with relative links), and gives an ordered reading path through the files inside it.
- **Lessons are numbered.** Use names like `01-foundational-concepts.md`, `02-presocratics.md`. Numbers mark the suggested order, not a claim that the history was that tidy.
- **Each lesson has the same spine:** a short **Prerequisites** line, a **Key ideas** list, the body, and a **Where this leads** section with relative links. Write enough to be useful (roughly 500–1200 words for lessons). Do not pad. Overviews of books, thinkers, and texts may use their own structure.
- **Cross-link with relative links.** When Greek ethics meets Confucian cultivation, or when a Gospel scene depends on an Exodus pattern, link it. Do not assume the reader is browsing in order.
- **Be accurate and even-handed.** Where a traditional reading and a scholarly one differ, say so plainly and leave the disagreement visible. This is a study tool, not a brief for a side.

## Top-level map

```
personal-encyclopedia/
  README.md
  SKILL.md             How a topic is added or expanded
  philosophy/
    concepts/          Granular lessons by branch
    glossary/          193 short entries (general, Greek, Chinese)
    history/
      ancient/
        greek/         Lessons, plus thinkers/ and texts/
        chinese/       Lessons, plus thinkers/ and texts/
        greek-and-chinese-compared.md
      imperial/        Song-Ming Confucian bridges (Zhu Xi, Wang Yangming)
  religion/
    abrahamic/
      christianity/
        bible/
          01–04 foundation lessons
          old-testament/   story lessons, stories/, books/ (all 39)
          new-testament/   survey lessons, stories/, books/ (all 27)
          deuterocanon/    Catholic and common Orthodox extras
          glossary/        228 entries (people, places, terms, themes)
```

Start here:

1. [Philosophy](philosophy/README.md) — what the discipline is, and the five branches that structure later questions.
2. [Ancient philosophy](philosophy/history/ancient/README.md) — then either the [Greek](philosophy/history/ancient/greek/README.md) or [Chinese](philosophy/history/ancient/chinese/README.md) path, and the [comparison](philosophy/history/ancient/greek-and-chinese-compared.md) after both.
3. [Religion](religion/README.md) — then [the Bible](religion/abrahamic/christianity/bible/README.md), its [book overviews](religion/abrahamic/christianity/bible/old-testament/books/README.md), and the [glossary](religion/abrahamic/christianity/bible/glossary/README.md).

Future topics should be added as new branches of this tree (for example `engineering/mechanical/…`), not as loose files at the root.

## References & further reading

- The process itself is in [SKILL.md](SKILL.md).
- Julia Annas, *Ancient Philosophy: A Very Short Introduction* (Beginner). A first book for the Greek side of the philosophy branch.
- Bryan W. Van Norden, *Introduction to Classical Chinese Philosophy* (Beginner). A first book for the Chinese side.
- John Barton, *A History of the Bible: The Book and Its Faiths* (Intermediate). A careful, readable overview of how the biblical library formed.
