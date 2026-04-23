# latex-templates

雙語說明（中文 / English）

概述
- **目的**：這個倉庫收藏各類 LaTeX 模板，方便建立與分享可重用的文件樣板（CV、報告、簡報等）。
- **目前內容**：包含一個單頁簡歷模板套件，位於 [single-page-cv/README.md](single-page-cv/README.md)。未來會陸續新增其他模板。

Overview
- **Purpose**: A collection of LaTeX templates for reuse and sharing (CVs, reports, slides, etc.).
- **Current contents**: One template package for a single-page CV — see [single-page-cv/README.md](single-page-cv/README.md). More templates may be added later.

Repository structure

```
(root)
- [single-page-cv/](single-page-cv/) — single-page CV template and development files.

```

How to use
1. Install a LaTeX distribution (TeX Live, MiKTeX, etc.).
2. Change into the template directory you want, for example:

	cd single-page-cv

3. Compile the example document:

	pdflatex main.tex

4. Or use your preferred LaTeX editor / toolchain (Overleaf, TeXstudio, VS Code + LaTeX Workshop).

How to add a new template
- Create a new top-level folder (e.g. `two-page-cv/`, `presentation/`) with a `main.tex` and a short `README.md` describing usage.
- Keep templates self-contained: include any template-specific .sty/.tex files in a `packages/` subfolder or reference common packages in a clear way.
- Add a brief note in this repository README or open a PR describing the new template.

Notes about the included single-page CV
- The single-page CV template is documented in [single-page-cv/README.md](single-page-cv/README.md). That README explains compilation, structure, and customization points.

Contributing
- Bug reports, improvements, and new template PRs are welcome. Please open an issue or submit a pull request with a concise description and example output.

License
- See the top-level `LICENSE` file for license terms governing this repository.

Contact / Support
- For questions or help customizing a template, open an issue in this repository.

---
Generated: concise repository README to index templates and usage.

