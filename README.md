# UNL Letter Class Options

## Installation

This template may be used standalone or through installation in a `texmf` directory.  If the latter is selected, copy the PDF files `Nebraska_N_4c.pdf` and `UNLlogo.pdf` and the file `unl.lco` to the appropriate locations in your TDS-compliant installation.

## Necessary Variables

You will need to set the following Koma variables:

 - `fromname`
 - `fromemail`
 - `fromdepartment`
 - `fromphone`
 - `fromoffice`
 - `fromurl`
 - `date` (It is recommended to use the `\printdate` macro for this)

You may also want to set:

 - `fromtitle` (your academic title)
 - `signaturefile` (a box which contains an image of your signature)

The `fromaddress` and `backaddress` variables are generated from the above.  If you would like a "back address" printed, set the options `addrfieold` and `backaddress` to true.

## Loaded Packages and Features

Features:

 - Sectioning commands are available (this is different from standard letter settings).
 - The color `huskerred` is defined.
 - Support for `envlab` to print envelopes is available with:
   ```latex
   \usepackage[businessenvelope,nocapaddress,pswait]{envlab}
   \makelabels
   ```
 - Multipage letters receive a two-line header including the name of the addressee, the date, and the page number.
 - The letterhead page includes folding marks.

Packages:

 - `url`
 - `xcolor`
 - `graphicx`
 - `babel` (set to `english`)
 - `isodate` (`cleanlook,american`)
 - `scrlayer-scrpage`
 - `textpos`

## Other Information

See also the [KOMA-Script manual](mirrors.ctan.org/macros/latex/contrib/koma-script/doc/scrguien.pdf) for further information.
