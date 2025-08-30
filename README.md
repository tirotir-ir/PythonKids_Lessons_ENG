<p align="center">
  <img src="tirotir-logo.svg" width="420" alt="Tirotir AI — Hoosh Masnooe">
</p>

<h1 align="center">TirotirPy — Python for Kids & Ultimate Cheatsheets</h1>
<p align="center">
  <b>Hoosh Masnooe — AI Training Center (Iran)</b> · <a href="https://tirotir.ir">tirotir.ir</a><br/>
  <a href="https://github.com/USER/REPO"><img src="https://img.shields.io/github/stars/USER/REPO?style=social" alt="GitHub stars"></a>
</p>

A classroom‑ready package for teaching Python with story‑based notebooks, plus a **huge one‑page Ultimate Reference** packed with examples, outputs, and mini how‑tos.
Updated: **2025-08-30**

## Contents
- **Notebooks (English)** — short, kid‑friendly lessons (story → unplugged activity → 3–5 lines of code → tiny challenge):
  - `PythonKids_EN_Part1_01-12.ipynb`
  - `PythonKids_EN_Part2_13-24.ipynb`
  - `PythonKids_EN_Part3_25-36.ipynb`
- **Cheatsheet Dashboard (EN)** — quick demos & downloads: `index.html`
- **Ultimate Reference (EN)** — single big page with search & copy buttons: `Python_TirotirPy_Combined_EN.html`
- Branding: `tirotir-logo.svg`

## Quick Start
1) Open the notebooks with **JupyterLab/Notebook** or **VS Code** (Python extension).  
2) Open the HTML files by double‑clicking (or serve with any static web server).  
3) Optional environment (recommended):
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install jupyter
```
> No external internet is required while teaching; all code examples are local and lightweight (GUI libs need a desktop environment).

## Ultimate Reference — What’s Inside
- **Expanded examples** for basics, control flow (`while` + `while/else`), strings & regex, slicing & strides, list/dict/set/tuple, functions (`*args/**kwargs`, `itertools`, `functools.lru_cache`), files (`pathlib`, CSV/JSON), `datetime`, exceptions, OOP + `@dataclass`, simple threading, and environment tips (`venv`, `pip`).
- **50 must‑know libraries** with `pip install` hints and tiny examples: requests, httpx, aiohttp, numpy, pandas, matplotlib, seaborn, scipy, scikit‑learn, sympy, statsmodels, pillow, opencv, pydub, pygame, pyttsx3, gTTS, SpeechRecognition, pyserial, pyautogui, selenium, beautifulsoup4, lxml, scrapy, fastapi, flask, django, sqlalchemy, alembic, psycopg2‑binary, PyMySQL, redis, celery, kafka‑python, pydantic, marshmallow, attrs, click, typer, rich, loguru, tqdm, schedule, APScheduler, paramiko, fabric, boto3, google‑cloud‑storage, azure‑storage‑blob, pytest, hypothesis.
- **20 hot tips & tricks**: f‑string debug (`{var=}`), enumerate start, `zip(*)` transpose, star‑unpack, `dict.get`/`setdefault`, `any`/`all`, custom `sorted(key=...)`, `contextlib.suppress`, `itertools.groupby`, `timeit`, walrus `:=`, comprehensions, specific exceptions, `@dataclass`, typing hints, `argparse`, better printing, stderr logging, and more.
- **Copy‑ready code** and **expected outputs** where helpful.

## PyInstaller — 30‑second Guide
Bundle your script into an executable (Windows/macOS/Linux):
```bash
python -m venv .venv
# Win: .venv\Scripts\activate    macOS/Linux: source .venv/bin/activate
pip install --upgrade pip pyinstaller

# One‑file build
pyinstaller --onefile app.py

# One‑file build without console
pyinstaller --onefile --windowed app.py

# Useful flags
# --noconsole  (GUI apps)    --icon=app.ico (.icns on macOS)
# --name MyApp  --hidden-import pkg.sub  --add-data "SRC;DEST" (Win)  or  "SRC:DEST" (macOS/Linux)

# Example: include 'assets' folder into the bundle (Win/macOS/Linux syntax differs)
pyinstaller --onefile --add-data "assets;assets" app.py   # Windows
pyinstaller --onefile --add-data "assets:assets" app.py   # macOS/Linux
```
Output will be under `dist/`. For best results, sign the binary or zip it before sharing.

## License
MIT — free for classrooms and open‑source projects. Attribution appreciated: **Tirotir AI — Hoosh Masnooe (tirotir.ir)**.

## Credits
Curated for educators and learners. Issues and PRs are welcome!
