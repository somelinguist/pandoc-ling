# pandoc-ling 1.3

## changes

- changed the ID system to "#ex:" for easier cross-document linking to examples
- change @next and @last to lowercase for easier typing

## bugs

- resolved clash with pandoc-crossref
- corrected wrong counting with unnumbered headings
- fixed counter reset and \exewidth with gb4e

# pandoc-ling 1.2

## changes

- adding experimental beamer as possible export. It uses the same routines as basic latex export. needs more testing.

## bugs

- fixed problem with parsing local options

# pandoc-ling 1.1

## changes

- adding experimental noFormat option to simply use the raw content of the example as a complete div to a single table cell and set number to vertically centred. For latex export, all lines are simply squashed together. needs more testing.

# pandoc-ling 1.0

First complete working version