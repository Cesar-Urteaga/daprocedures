# Building R Packages Pre-Flight Check List

1. Install latest version of R
2. Install latest version of RStudio
3. Open RStudio
4. Install `devtools` package (may take a few minutes) or update packages
4. Install `roxygen2` package
5. Click on Project ---> New Project… ---> New Directory ---> R Package
7. Enter package name
9. Verify that project **subdirectory** name does not contain any spaces
8. Click "Create Project"
8. Delete bolierplate code and `hello.R` file in the `R` directory
9. Goto the `man` directory and delete the `hello.Rd` file
9. In File browser, click on the package name to go to the top level directory
10. Click “Build” tab in environment browser
14. Click More ---> “Configure Build Tools…”
15. Check “Generate documentation with Roxygen” --> Click the "Configure..." button
16. Check “Build & Reload” in the Roxygen Options —> Click OK
17. Click OK in Project Build Tools Options

