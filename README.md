<p align="center">
  <img src="tirotir-logo.svg" width="420" alt="Tirotir AI — Hoosh Masnooe (AI Training Center)">
</p>

<h1 align="center">TirotirPy — Ultimate Python Cheatsheet & Kids Notebooks (EN + Persian RTL)</h1>

<p align="center">
  <b>Python quick reference, teaching resources, and story-based notebooks</b><br/>
  Keywords: python cheatsheet, quick reference, education, kids, jupyter notebooks, tkinter, turtle, pyinstaller, numpy, pandas, matplotlib, persian rtl
</p>

<p align="center">
  <a href="https://github.com/USER/REPO"><img alt="GitHub stars" src="https://img.shields.io/github/stars/USER/REPO?style=social"></a>
  <a href="LICENSE"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-blue.svg"></a>
  <a href="https://tirotir.ir"><img alt="Tirotir AI" src="https://img.shields.io/badge/Tirotir-AI-00bcd4"></a>
  <a href="#contributing"><img alt="PRs welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"></a>
</p>

A classroom‑ready toolkit that combines **a huge one‑page Ultimate Python reference** with **kid‑friendly lesson notebooks**. Everything is designed for **teachers**, **self‑learners**, and **Persian (RTL) classrooms**.

---

## Table of Contents
- [Highlights](#highlights)
- [Live Demo / Files](#live-demo--files)
- [Install & Run](#install--run)
- [Ultimate Reference (What’s Inside)](#ultimate-reference-whats-inside)
- [Notebooks (English)](#notebooks-english)
- [PyInstaller Quick Guide](#pyinstaller-quick-guide)
- [Screenshots](#screenshots)
- [SEO Tips for This Repo](#seo-tips-for-this-repo)
- [Suggested GitHub Topics](#suggested-github-topics)
- [FAQ](#faq)
- [Contributing](#contributing)
- [License](#license)

## Highlights
- **Ultimate Cheatsheet**: searchable cards, **copy buttons**, examples with **expected output** and notes.
- **Education‑first**: short, story‑driven **Jupyter notebooks** for kids and beginners.
- **Bilingual**: English + **Persian (RTL)** support across materials.
- **Practical add‑ons**: 50 must‑know libraries, **PyInstaller** packaging, CLI tips, GUI basics (tkinter/turtle).
- **Branding ready**: includes `tirotir-logo.svg` and placeholders for GitHub stars & Pages.

## Live Demo / Files
> On GitHub, HTML previews may not render. For a live view, **enable GitHub Pages** (Settings → Pages → “Deploy from branch” → main).  
> Then the links below will open as web pages.

- **Ultimate Cheatsheet (EN)** → `Python_TirotirPy_Combined_EN.html`  
- **Dashboard (EN)** → `PythonKids_CheatSheet_Dashboard_EN.html`  
- **Logo** → `tirotir-logo.svg`

- **Live Demo (GitHub Pages)**: https://tirotir-ir.github.io/PythonKids_Lessons_ENG/index.html

## Install & Run
```bash
# 1) (Recommended) create a virtual environment
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate

# 2) Tools for notebooks
pip install jupyter

# 3) Open notebooks
jupyter lab  # or: jupyter notebook
```
No network is required to use the cheatsheets (GUI libs need a desktop environment).

## Ultimate Reference (What’s Inside)
- **Core language**: print/type, while/while‑else, slicing & strides, list/dict/set/tuple, exceptions, OOP + `@dataclass`.
- **Functions**: `*args/**kwargs`, comprehensions, `itertools`, `functools.lru_cache`.
- **Files & data**: `pathlib`, CSV/JSON, `datetime`.
- **Env & tooling**: `venv`, `pip`, mini **PyInstaller** how‑to.
- **50 libraries** with `pip install` and tiny examples: requests, httpx, aiohttp, numpy, pandas, matplotlib, seaborn, scipy, scikit‑learn, sympy, statsmodels, pillow, opencv, pydub, pygame, pyttsx3, gTTS, SpeechRecognition, pyserial, pyautogui, selenium, beautifulsoup4, lxml, scrapy, fastapi, flask, django, sqlalchemy, alembic, psycopg2‑binary, PyMySQL, redis, celery, kafka‑python, pydantic, marshmallow, attrs, click, typer, rich, loguru, tqdm, schedule, APScheduler, paramiko, fabric, boto3, google‑cloud‑storage, azure‑storage‑blob, pytest, hypothesis.
- **20 hot tips**: f‑string debug, enumerate start, `zip(*)`, star‑unpacking, `dict.get`/`setdefault`, `any`/`all`, custom `sorted(key)`, `contextlib.suppress`, `itertools.groupby`, `timeit`, walrus `:=`, comprehensions, `@dataclass`, typing hints, `argparse`, stderr logging, etc.

## Notebooks (English)
- `PythonKids_EN_Part1_01-12.ipynb`
- `PythonKids_EN_Part2_13-24.ipynb`
- `PythonKids_EN_Part3_25-36.ipynb`

These follow a consistent flow: **story → unplugged activity → tiny code → mini challenge**.

## PyInstaller Quick Guide
```bash
pip install --upgrade pyinstaller

# One-file build
pyinstaller --onefile app.py

# Useful flags
# --noconsole (GUI apps), --icon=app.ico (.icns on macOS)
# --name MyApp, --hidden-import pkg.sub, --add-data

# Add data (Windows uses ';' — macOS/Linux use ':')
pyinstaller --onefile --add-data "assets;assets" app.py   # Windows
pyinstaller --onefile --add-data "assets:assets" app.py   # macOS/Linux
```
Output appears under `dist/`. For distribution, consider **signing** or **zipping** the binary.

## Screenshots
> Add screenshots or GIFs here for better engagement and SEO (descriptive alt text helps):
- `docs/screenshot-cheatsheet.png` — *Ultimate Cheatsheet home*
- `docs/screenshot-notebook.png` — *Kids notebook lesson*
- `docs/screenshot-pyinstaller.png` — *PyInstaller one‑file build*

## SEO Tips for This Repo
- **Make repo Public** and fill the **About** box with a one‑line description + your site (`https://tirotir.ir`).  
- Add **10–20 Topics** (see below). Topics & headings help GitHub search.  
- Upload a **Social preview** image (Settings → Social preview; 1280×640) so shares look great.  
- Pin this repo on your profile and publish **Releases** with short notes.  
- Consider a `CITATION.cff` so “Cite this repository” appears automatically.  
- Enable **Pages** to host the HTML cheatsheet (then link it above as a live demo).

## Suggested GitHub Topics
`python, cheatsheet, quick-reference, jupyter-notebook, education, kids, teaching, tkinter, turtle, pyinstaller, text-to-speech, colorama, termcolor, numpy, pandas, matplotlib, ai-education, persian, rtl, tirotir, hoosh-masnooe`

## FAQ
**Q: HTML doesn’t render on GitHub.**  
A: Enable **GitHub Pages** and open the link from the Pages site, or run a local static server.

**Q: Copy buttons don’t work locally.**  
A: They should now (Clipboard API + fallback). If blocked by the browser, try a local server (e.g., `python -m http.server`).

**Q: Turtle/tkinter window not showing in VS Code?**  
A: Run the script in an **external terminal** or disable the “Run in Integrated Terminal” setting for GUI apps.

**Q: Persian RTL support?**  
A: The notebooks and dashboards can include RTL blocks; the content here includes Persian terms and can be mirrored easily.

## Contributing
Issues and PRs are welcome—especially lesson ideas, Persian translations, and beginner‑friendly examples.

## License
MIT — © Tirotir AI / Hoosh Masnooe.  
Updated: **2025-08-30**
