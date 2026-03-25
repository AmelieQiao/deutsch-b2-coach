# Materials

This folder stores all study materials for my German exam preparation system.

The purpose of this folder is not only storage, but also structured use:
- define preparation scope
- support baseline assessment
- support targeted weak-area practice
- support long-term tracking and review

## Core principle
Materials should be organized by:
1. level
2. skill type
3. source type

The system should always understand:
- which materials are foundation-level
- which materials are bridge-level
- which materials are target-level
- which materials are mainly for reading
- which materials are mainly for writing
- which materials are mainly for grammar
- which materials are mainly for vocabulary

## Level structure

### A2
Use A2 materials for:
- identifying missing foundation
- repairing grammar gaps
- repairing basic sentence structure problems
- repairing essential reading and writing weaknesses

### B1
Use B1 materials for:
- transition training
- strengthening control of common structures
- improving reading and writing stability
- bridging from foundation to target level

### B2
Use B2 materials for:
- target-scope preparation
- exam-oriented reading and writing practice
- advanced grammar in practical use
- formal and semi-formal written expression
- reusable Redemittel and collocations

## Recommended folder structure

materials/
├── A2/
│   ├── exams/
│   ├── reading/
│   ├── writing/
│   ├── grammar/
│   └── vocab/
├── B1/
│   ├── exams/
│   ├── reading/
│   ├── writing/
│   ├── grammar/
│   └── vocab/
├── B2/
│   ├── exams/
│   ├── reading/
│   ├── writing/
│   ├── grammar/
│   └── vocab-redemittel/
└── misc/
    ├── reference/
    └── temporary/

## Folder purposes

### exams/
Store:
- full past papers
- mock exams
- official-style exam tasks
- scanned or photographed exam materials

Use for:
- baseline testing
- level estimation
- timed practice
- weak-area retesting

### reading/
Store:
- reading passages
- reading exercises
- comprehension tasks
- text-analysis materials

Use for:
- reading comprehension training
- vocabulary extraction
- text structure analysis
- strategy practice

### writing/
Store:
- writing prompts
- model answers
- writing drills
- formal / semi-formal response tasks
- summary tasks
- opinion / argument tasks
- forum / comment / proposal response tasks

Use for:
- task-type training
- structure training
- Redemittel training
- grammar-in-writing practice

### grammar/
Store:
- grammar summaries
- grammar exercises
- focused drills
- contrast sheets
- tables and pattern notes

Use for:
- targeted weak-area repair
- function-based grammar review
- pattern comparison
- error correction

### vocab/
Store:
- vocabulary lists
- phrase lists
- collocations
- Redemittel sheets
- function-based expression lists

Use for:
- building usable vocabulary
- improving writing range
- improving reading recognition
- collecting reusable expressions

### misc/
Store:
- reference documents
- temporary files
- uncategorized files before sorting

Use for:
- short-term holding
- later classification
- non-core support materials

## Naming suggestions

Use practical and searchable file names.

Recommended style:
- `A2_Modelltest_01.pdf`
- `B1_Lesen_Textanalyse_01.pdf`
- `B2_Schreiben_Zusammenfassung_01.pdf`
- `B2_Grammatik_Passiv_01.pdf`
- `B1_Redemittel_Meinung_und_Begruendung.pdf`

If useful, include:
- level
- skill
- topic
- sequence number

## Material usage rules for Claude

When using materials from this folder, Claude should:
1. identify the level
2. identify the skill type
3. identify the task type
4. identify the target grammar / Redemittel / vocabulary function
5. estimate whether the material is foundation repair, bridge practice, or target-scope practice
6. extract reusable patterns
7. connect the material to current weak areas
8. save key findings into session and progress files

## Priority order
Current priority should usually be:

1. uploaded exams and official-style tasks
2. grammar materials
3. reading materials
4. writing materials
5. vocabulary / Redemittel support materials

Priority may change if baseline assessment shows a major weakness.

## Notes
- A2 materials are not “too easy” if they reveal missing foundations
- B1 materials are important bridging tools
- B2 materials define the target scope
- Materials should support actual progress, not passive collection

---

## How to add a new PDF (e.g. reading training book)

### On your Mac (local)

1. Pick a folder that matches level + skill, for example:
   - `materials/A2/reading/` — foundation reading drills
   - `materials/B1/reading/` — bridge reading
   - `materials/B2/reading/` — target-level reading
2. Copy the PDF into that folder. Use a **clear filename**, e.g. `A2_Lesetraining_Kapitel_01.pdf`.
3. (Optional) If the repo is new, run in the project root:
   - `git add materials/…/your-file.pdf`
   - `git commit -m "Add reading training PDF"`
   - `git push` to your GitHub remote (after `git remote add` if needed).

### Sync with GitHub

- **Push:** after `commit`, `git push` uploads new PDFs.
- **Pull:** on another machine, `git pull` to receive the same files.
- Large PDFs: if GitHub warns about size, use Git LFS or store outside the repo — tell the coach if that applies.

After the file is in `materials/`, the coach will **read/index** it and schedule passages for **intensive reading** in `sessions/YYYY-MM-DD/reading-intensive.md`.
