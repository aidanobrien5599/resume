# Resume

## Local Setup (macOS)

1. Install BasicTeX via Homebrew:
   ```
   brew install --cask basictex
   ```

2. Restart your terminal, then install required LaTeX packages:
   ```
   sudo tlmgr update --self
   sudo tlmgr install fontawesome enumitem fancyhdr titlesec preprint babel-english marvosym
   ```

3. Compile the resume:
   ```
   pdflatex resume.tex
   ```

This generates `resume.pdf` in the same directory.