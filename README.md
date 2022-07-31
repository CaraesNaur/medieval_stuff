# medieval_stuff
Various documents relevant to Medieval insterests

##prices_list.ods

LibreOffice Calc spreadsheet containing various Medieval-era prices for
goods & services (and some wages).

This file started as the famous Medieval Price List published by
[Kenneth Hodges](https://liberalarts.vt.edu/departments-and-schools/department-of-english/faculty/kenneth-hodges.html).  Other sources include:

* http://www.medievalcoinage.com/prices/medievalprices.htm
* https://www.economics.utoronto.ca/munro5/SPICES1.htm
* Others that I found individually

Note: the HTML version of the Hodges list I started with is timestamped
25 April 2001, which seems to predate any version currently available.

The purpose here is an attempt to normalize prices to a given year with
some modicum of accuracy.  Medieval prices are few and and vary wildly
due to various factors, so perfect accuracy may not be possible.

To wit, cells T1 through Y1 allow the given prices to be normalized
according to a very basic (likely inaccurate) inflation formula.

Columns:

* A: Item descritpion
* B: Price (L s d)
* C: Pence Min
* D: Pence Max
* E: Decimalized Pence Min
* F: Decimalized Pence Max
* G: ca. 1330 Adjusted Pence
* H: NX (normalized) Price Min
* I: NX (normalized) Price Max
* J: Date (year)
* K: Decade (approximated from year)
* L: Source
* M: Page
* N: (unused)
* O: NX Min dWt Adj'd (Normalized pennyweight Adjusted)

"Decimalized" means the d values have been refactored to 100d per base
unit (L).

"Normalized"/"NX" means decimalized values with the formula applied.

Pennyweight (dwt) factor is an adjustment meant to maintain the same
weight of silver under the decimalized currency scheme.

Columns G and K are conditionally formatted based on the value rages.

Blue and gray rows form sections and sub-sections, respectively.
