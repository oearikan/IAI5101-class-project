# IAI5101/SYS5185/GNG5300 - Foundation and Applications of Machine Learning
Winter 2026 - University of Ottawa

## About using LaTeX
The project requires to submit proposal in neurips format. Corresponding .sty and .tex files are provided. We don't need to touch the .sty file. All edits are to be made in .tex file (use github's browser interface to edit if you want) and once finished editing, we have to compile it for submission ready pdf.  

Below is a non-detailed overview of how to create the pdf for submission:  
**Prerequistes:** 
- Download a builder from MiKTeX (https://miktex.org/download)
- You need to have Perl installed.

**In Powershell:**  
```pdflatex -jobname="proposal" neurips_2025.tex```
