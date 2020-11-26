# Typeset docs

Includes a **one-page** résumé template in **XeTeX** based on [Matthew Butterick's Practical Typography example Résumé](http://practicaltypography.com/resumes.html) and [a LaTeX implementation of that example](https://github.com/thnatiw/edelgas-resume).

## Preview

## Dependencies

1. Designed with Matthew Butterick's [**Equity**](http://practicaltypography.com/equity.html) and [**Concourse**](http://practicaltypography.com/concourse.html) fonts in mind, which are available to buy on the [**Practical Typography**](http://practicaltypography.com/) website. 

  For alternatives to the serif and sans fonts, please read:
  * Sans: [Helvetica & Arial alternatives](http://practicaltypography.com/helvetica-and-arial-alternatives.html)
  * Serif: [Times New Roman alternatives](http://practicaltypography.com/times-new-roman-alternatives.html)

2. Compiles only with `xelatex`. (see Package dependencies)

## XeTeX package dependencies

Uses the following packages (which are available in your preferred TeX-distribution): xunicode, xltxtra, fontspec (for using any font), geometry (custom margins), ifmtarg (check for empty arguments), listings and enumitem (for more flexible enumerations), csquote (quotation marks), fancyhdr (custom header), lastpage (to count the pages).

## Known Issues:

* CJK doesn't work in Times New Roman. The xeCJK package removes **all** whitespaces in non CJK passages. Either declare an new command for passages in CJK or try to resort to font that supports UTF8 characters. Alternatively set it in CJK throughout the whole document.

* Butterick already included his recommended letterspacing in his fonts. This could clash with the custom letterspacing defined in the cls. If you are changing your font, please check the output file and adjust it to your taste.

## License

You are free to use these templates in any way you wish.

Just keep in mind that the idea came from Matthew Butterick, so please buy his book or his fonts. For more information visit [his website](http://practicaltypography.com/how-to-pay-for-this-book.html).
