.tex file generated from .txt file via Txt2LaTeX.py file, with no additional arguments (.txt was copied from a .pdf with no running headers/footers)

python Txt2LaTeX.py "NewGlobalJournalism.txt" ""

generate html w/pandoc:

pandoc PostIndustrialJournalism.tex -o PostIndustrialJournalism.html

Create CMS-ready files:
python CreateRightRail.py PostIndustrialJournalism.html


generate md w/pandoc:

pandoc PostIndustrialJournalism.tex -o PostIndustrialJournalism.md

Generate GitBook files:
python CreateRightRail.py PostIndustrialJournalism.html


