
# testExcessiveImports

<!-- badges: start -->
<!-- badges: end -->

Minimal example of `devtools::check()` not using the `_R_CHECK_EXCESSIVE_IMPORTS_` environment variable.

Running Check in RStudio 1.3.1073 with R 4.0.2 on Windows 10 gives a note about the 21 imports.

Running `devtools::check()` gives the same note.

Running `devtools::check(env_vars = c("_R_CHECK_EXCESSIVE_IMPORTS_" = "30"))` gives the same note.
