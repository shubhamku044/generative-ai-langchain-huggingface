# Complete Generative AI Course — Learning Notes

My section-wise notes, code and notebooks from **[Complete Generative AI Course With Langchain and Huggingface](https://www.udemy.com/course/complete-generative-ai-course-with-langchain-and-huggingface/)** by [Krish Naik](https://www.udemy.com/user/krish-naik/).

> 56 sections • 258 lectures • ~70 hrs — from NLP fundamentals to LangChain, Hugging Face, RAG, agents and end-to-end GenAI projects.

## Why this repo exists

- Learn in public: notes + runnable code for every section I complete
- Track progress honestly with the checklist below
- Help others following the same course skip the potholes I hit

## Progress

| # | Section | Status |
|---|---------|--------|
| 1 | Introduction | ⏭️ Skipped (known) |
| 2 | Python Control Flow | ⏭️ Skipped (known) |
| 3 | Data Structures Using Python | ⏭️ Skipped (known) |
| 4 | Functions In Python | ⏭️ Skipped (known) |
| 5 | Importing, Creating Modules And Packages | ⏭️ Skipped (known) |
| 6 | File Handling In Python | ⏭️ Skipped (known) |
| 7 | Exception Handling | ⏭️ Skipped (known) |
| 8 | OOPS Classes And Objects | ⏭️ Skipped (known) |
| 9 | Streamlit With Python | ⬜ Not started |
| 10 | [Machine Learning For NLP (Prerequisites)](sections/10-machine-learning-for-nlp/) | 🔄 In progress |
| 11+ | _added as I reach them_ | ⬜ |

Legend: ⬜ not started · 🔄 in progress · ✅ done · ⏭️ skipped

## Repo structure

```
sections/
└── 10-machine-learning-for-nlp/
    ├── README.md        # section overview + lecture checklist
    ├── notes.md         # my written notes, lecture by lecture
    └── notebooks/       # runnable Jupyter notebooks for the section
```

Every section I start gets the same skeleton — copy it from section 10.

## Setup (uv)

This repo uses [uv](https://docs.astral.sh/uv/) for reproducible environments. Python version and all dependencies are pinned in `pyproject.toml` + `uv.lock`.

```bash
git clone https://github.com/<your-username>/generative-ai-langchain-huggingface.git
cd generative-ai-langchain-huggingface

uv sync                # creates .venv, installs pinned deps
uv run jupyter lab     # work through notebooks
```

No Python install needed — uv fetches the pinned 3.12 interpreter automatically.

## Workflow I follow

1. Watch the lecture
2. Write the gist in the section's `notes.md` — in my own words, formulas + diagrams where useful
3. Re-implement the practicals in `notebooks/` (not copy-paste)
4. Commit and push

```bash
git add . && git commit -m "sec 10: tf-idf notes + notebook" && git push
```

## License

MIT — use the notes however they help you. Course content belongs to Krish Naik / KRISHAI Technologies; buy the course for the videos.
