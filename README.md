# Personal encyclopedia

A private collection of notes and short courses on topics of interest. It is organized as a discipline tree: folders of markdown files, nested the way a field is actually built, not the way a casual question is usually asked.

## First-principles approach

When a topic is added here, the goal is not to jump straight to a finished explanation of that topic. The goal is to teach the underlying concepts that make the topic intelligible.

If the question is "how does an internal combustion engine work?", the path should run through something like `engineering/mechanical/thermodynamics/` (heat, work, cycles, combustion) before the engine itself appears. The thing asked about usually sits lower in the tree, after its prerequisites, not at the top level.

This does two things. It keeps the library honest about dependence: you cannot really understand an engine without heat and work, or Aristotle without the problem of change, or the Gospels without Second Temple Judaism. It also means later topics can reuse earlier ones instead of repeating them.

## Folder conventions

- **Nest by discipline.** Place a subject under the broader field it belongs to. Resist putting a proper name or a gadget at the root just because that was the prompt.
- **Every folder has a `README.md`.** That file says what the folder is, lists prerequisites (with relative links), and gives an ordered reading path through the files inside it.
- **Lessons are numbered.** Use names like `01-foundational-concepts.md`, `02-presocratics.md`. Numbers mark the suggested order, not a claim that the history was that tidy.
- **Each lesson has the same spine:** a short **Prerequisites** line, a **Key ideas** list, the body, and a **Where this leads** section with relative links. Write enough to be useful (roughly 300–900 words). Do not pad.
- **Cross-link with relative links.** When Greek ethics meets Confucian cultivation, or when a Gospel scene depends on an Exodus pattern, link it. Do not assume the reader is browsing in order.
- **Be accurate and even-handed.** Where a traditional reading and a scholarly one differ, say so plainly and leave the disagreement visible. This is a study tool, not a brief for a side.

## Top-level map

```
personal-encyclopedia/
  README.md
  philosophy/          What philosophy is, and its core branches
    history/
      ancient/
        greek/         First principles of Greek thought, through the Hellenistic schools
        chinese/       First principles of early Chinese thought, through the Hundred Schools
        greek-and-chinese-compared.md
  religion/
    abrahamic/
      christianity/
        bible/         What the Bible is (canon, languages, composition, genres)
          old-testament/
          new-testament/
```

Start here:

1. [Philosophy](philosophy/README.md) — what the discipline is, and the five branches that structure later questions.
2. [Ancient philosophy](philosophy/history/ancient/README.md) — then either the [Greek](philosophy/history/ancient/greek/README.md) or [Chinese](philosophy/history/ancient/chinese/README.md) path, and the [comparison](philosophy/history/ancient/greek-and-chinese-compared.md) after both.
3. [Religion](religion/README.md) — then [the Bible](religion/abrahamic/christianity/bible/README.md), before any particular story.

Future topics should be added as new branches of this tree (for example `engineering/mechanical/…`), not as loose files at the root.
