# vallender-pkgdown-theme
A css theme for vallender lab pkgdown documentation.

## Usage

If you are using `pkgdown` to document an R package, create a `pkgdown` directory in the root of the package and add the `extra.css` file to that directory.

```r
dir.create('pkgdown')

# For Windows
download.file(url = "https://raw.githubusercontent.com/vallenderlab/vallender-pkgdown-theme/master/extra.css", 
              destfile = "pkgdown/extra.css", 
              method = "wininet")
```
