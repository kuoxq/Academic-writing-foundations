# Academic Writing Foundations

Academic Writing Foundations is a Codex skill for guiding foundational academic research-paper writing. It helps users move from a broad topic or messy draft toward a clear research question, paper outline, argument map, and revision plan.

## What This Skill Helps With

- Narrowing broad academic topics into feasible research scopes
- Designing research problems, research questions, and working theses
- Building paper outlines with clear section purposes
- Organizing literature review sections by theme, debate, theory, method, or chronology
- Mapping claims, evidence, analysis, and transitions
- Drafting or revising introductions, discussion sections, and academic arguments
- Diagnosing structural problems before sentence-level polishing

## When to Use It

Use this skill when a user says things like:

- "I do not know how to organize this paper."
- "Help me turn this topic into a research question."
- "Can you make an outline for my academic paper?"
- "My introduction, literature review, or discussion section is messy."
- "Teach me how to structure an academic research paper."

This skill is especially useful before using heavier research workflows, when the user does not yet have a clear research question, structure, or argument map.

## Relationship to Other Skills

- Use `academic-research-suite` for deep research, literature discovery, systematic review, citation verification, full paper pipelines, peer review simulation, or experiment planning.
- Use `academic-phrasebank` when the argument and structure are stable but the user needs more idiomatic academic English.
- Use `zotero` for local library search, BibTeX export, and citation-key insertion.
- Use `Scite` or web verification when claims require source-grounded evidence.
- Use `documents` when the user needs a polished `.docx` artifact.

## Installation

Clone this repository into your Codex skills directory:

```bash
git clone https://github.com/kuoxq/kuoxq-academic-writing-foundations.git ~/.codex/skills/academic-writing-foundations
```

Then invoke it in Codex with:

```text
Use $academic-writing-foundations to turn my broad paper topic into a research question, outline, and revision checklist.
```

## Repository Structure

```text
.
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    └── shu-framework-and-skill-map.md
```

## Source Inspiration

The skill is inspired by university library guidance on organizing academic research papers, especially the practical writing competencies reflected in Sacred Heart University Library's research paper organization guide. It converts those competencies into a reusable Codex workflow for topic narrowing, paper architecture, argument mapping, and revision.
