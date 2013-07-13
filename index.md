---
layout: default
title: WriteXLSX
---

# WriteXLSX
This is a reference of WriteXLSX (write_xlsx) rubygem.

## DESCRIPTION
The WriteXLSX rubygem can be used to create an Excel file in the 2007+ XLSX format.

This is ported to Ruby from Perl module [Excel::Wirter::XLSX](http://search.cpan.org/~jmcnamara/Excel-Writer-XLSX-0.70/).

The XLSX format is the Office Open XML (OOXML) format used by Excel 2007 and later.

Multiple worksheets can be added to a workbook and formatting can be applied to cells.
Text, numbers, and formulas can be written to the cells.

This module cannot, as yet, be used to write to an existing Excel XLSX file.

WriteXLSX uses the same interface as the Writeexcel rubygem which produces an Excel file in binary XLS format.
WriteXLSX supports all of the features of Writeexcel and in some cases has more functionality. For more details see ["Compatibility with Writeexcel"](compatibility_with_writeexcel.html).

The main advantage of the XLSX format over the XLS format is that it allows a larger number of rows and columns in a worksheet.
The XLSX file format also produces much smaller files than the XLS file format.
