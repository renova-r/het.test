# het.test 0.1.9001

Renova release, based on CRAN het.test 0.1 (archived on CRAN 2021-02-15).

- `NAMESPACE`: added `importFrom()` directives for `methods` (`new`, `setClass`, `setMethod`, `representation`, `show`), `stats` (`lm`, `pchisq`, `residuals`) and `vars` (`VAR`); trailing spaces removed from the `exportMethods`/`exportClasses` entries. `DESCRIPTION` gains `Imports: stats`; `Depends: vars, methods` is unchanged.
- `R/white_r.R`: the four input checks in `whites.htest()` compare `class(...)[1L]` to a string, so they no longer fail when an object has more than one class.
- `man/het.test.Rd`: the package help page is named `het.test-package` (was the invalid `het.htest-package`), gains the `het.test` alias, and the multi-term `\keyword{}` was replaced by `\keyword{htest}` (documentation only).
- `DESCRIPTION`: `Author` changed from "Sebastian Andersson" to "Sebastian Andersson [aut, cre]" and an equivalent `Authors@R` entry was added; `Maintainer` is unchanged (metadata only).
- `DESCRIPTION`: the stale optional `Date: 2013-02-27` field was removed (metadata only).
- `DESCRIPTION`: `Version` set to `0.1.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 2 text) was added; the `License` field is unchanged.
- `README.md` was added and `.Rbuildignore` keeps `README.md` and `NEWS.md` out of the built package.
