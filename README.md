# xelatex-template
<p align="center">
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/favicon.ico" />
</p>

## Description
(Xe)LaTeX template for BSTU papers. 

Before build of the PDF file you need to add `sign.png` (800x800) file with your signature into `./tex-source/` folder. It would be displayed next to your name (*most of the time* it's allowed in BSTU).
**Another solution** is to replace code that put sign on the page with `\vspace{}`

For listings used slightly modified [gruvbox](https://github.com/morhetz/gruvbox)-light color scheme.

Page parameters:
  - Main font - Times New Roman, 14pt
  - Listings font - Cascadia Code, 9pt
  - Parindent - 1.25
  - Linespread - 1.3
  - Page indents - left=3cm, right=1.5cm, top=2cm, bottom=2cm, headsep=1cm, footskip=1cm

## Languages in lstlistings
Tested:
  - C
  - C++
  - C# (custom, name: CSharp)
  - Python
  - Rust (custom, name: Rust)
  - ASM (custom, name: ASM)

<details>
<summary>Theoretically supported:</summary>
  - ABAP
  - ACSL
  - Ada
  - Algol
  - Ant
  - Assembler
  - Awk
  - bash
  - Basic
  - Caml
  - CIL
  - Clean
  - Cobol
  - Comal 80
  - csh
  - Delphi
  - Eiffel
  - Elan
  - erlang
  - Euphoria
  - Fortran
  - GCL
  - Cnuplot
  - Haskell
  - HTML
  - IDL
  - inform
  - Java
  - JVMIS
  - ksh
  - Lingo
  - Lisp
  - Logo
  - make
  - Mathematica
  - Matlab
  - Mercury
  - MetaPost
  - Miranda
  - Mizar
  - ML
  - Modula-2
  - MuPAD
  - NASTRAN
  - Oberon-2
  - OCL
  - Octave
  - Oz
  - Pascal
  - Perl
  - PHP
  - Pl/I
  - Plasm
  - PostScript
  - POV
  - Prolog
  - Promela
  - PSTricks
  - Python
  - R
  - Reduce
  - Rexx
  - RSL
  - Ruby
  - S
  - SAS
  - Scilab
  - sh
  - SHWLXL
  - Simula
  - SPARQL
  - SQL
  - tcl
  - TeX
  - VBScript
  - Verilog
  - VHDL
  - VRML
  - XML
  - XSLT
</details>

## Setting up
### Windows
To set up this template simpy run script `tex-setup.ps1`. It will delete git files (and itself) and will allow to put `.tex` directly into your own repo.

### Linux
Run script `tex-setup.sh`. It will delete git files (and itself) and will allow to put `.tex` directly into your own repo.

## Screenshots
<p align="center">
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/xelatex-template-1.png" width=700"/>
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/xelatex-template-2.png" width=700/>
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/xelatex-template-3.png" width=700/>
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/xelatex-template-4.png" width=700/>
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/xelatex-template-5.png" width=700/>
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/xelatex-template-6.png" width=700/>
  <img src="https://raw.githubusercontent.com/Kseen715/imgs/main/xelatex-template-7.png" width=700/>
</p>
