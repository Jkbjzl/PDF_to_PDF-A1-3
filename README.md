# PDF_to_PDF-A1-3
Script to converts all PDF files to PDF/A 1-3 incl. folder structure.

Simple Python script uses GPL Ghostscript https://ghostscript.com/releases/gsdnld.html and converts PDF content to PDF/A desired version. Can be used for mass purposes, it mirrors whole folder structere and converst every PDF to PDF/A in new structure. Except Ghostcript it requires Py pip Ghostcript module https://pypi.org/project/ghostscript/ and pip unidecode https://pypi.org/project/Unidecode/ module too. Unidecode is used just to normalize files namens to prevent problems with diacritics. 

Don´t forget to change command depending on your OS. 
