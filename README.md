# LaTeX Packages Installation

Sample global LaTeX package installation:

```bash
cd ${HOME}/texmf/tex/latex
wget https://mirrors.ctan.org/macros/latex/required/amsmath.zip
unzip amsmath.zip
rm amsmath.zip
```

Source <https://www.maths.cam.ac.uk/computing/software/tex/package>

Search LaTeX packages at [here](https://ctan.org/)

# LaTeX `texlive` installation

## Ubuntu/Debian

```bash
sudo apt install texlive-full
sudo apt install texlive-latex-extra
```

# List of installed packages

- [algorithmicx](https://mirrors.ctan.org/macros/latex/contrib/algorithmicx.zip)
    - Requires `texlive-science` for `algorithm.sty`
    - `sudo apt install texlive-science`
- [amsmath](https://mirrors.ctan.org/macros/latex/required/amsmath.zip)
- [enumitem](https://mirrors.ctan.org/macros/latex/contrib/enumitem.zip)
- [geometry](https://mirrors.ctan.org/macros/latex/contrib/geometry.zip)
- [graphics](https://mirrors.ctan.org/macros/latex/required/graphics.zip) (graphicx)
- [preprint](https://mirrors.ctan.org/macros/latex/contrib/preprint.zip) (fullpage)
- [pgf](https://www.ctan.org/pkg/pgf) (tikz)
- [varwidth](https://mirrors.ctan.org/macros/latex/contrib/varwidth.zip)
- [xcolor](https://mirrors.ctan.org/macros/latex/contrib/xcolor.zip)

