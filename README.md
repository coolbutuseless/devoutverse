
<!-- README.md is generated from README.Rmd. Please edit that file -->

# devoutverse <img src="man/figures/logo.png" align="right" height=230/>

<!-- badges: start -->

![](http://img.shields.io/badge/cool-useless-green.svg)
![](http://img.shields.io/badge/mini-verse-blue.svg)
<!-- badges: end -->

The `devoutverse` is a collection of packages offering non-standard
devices for RStats. Most are based on
[`devout`](https://github.com/coolbutuseless/devout).

The purpose of this `devoutverse` package is to:

1.  Provide links to the various packages.

## Installation

You can install `devoutverse` packages from
[GitHub](https://github.com/coolbutuseless/) with:

``` r
# install.packages("devtools")
devtools::install_github("coolbutuseless/devout")
devtools::install_github("coolbutuseless/devoutpdf")
devtools::install_github("coolbutuseless/devoutaudio")
devtools::install_github("coolbutuseless/devoutsvg")
```

<br />

|                                                                                                                                                                                                                                                        |                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                     |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="man/figures/logodevout.png"><br/> ASCII graphics device<br/><a href="http://github.com/coolbutuseless/devout">Github</a><br/> <a href="http://coolbutuseless.github.io/package/devout">Online documentation</a>                              | <img src="man/figures/logodevoutpdf.png"> <br/>PDF device<br/><a href="http://github.com/coolbutuseless/devoutpdf">Github</a><br/> <a href="http://coolbutuseless.github.io/package/devoutpdf">Online documentation</a> | <img src="man/figures/logodevoutaudio.png"><br/> Audio output for graphics device<br/><a href="http://github.com/coolbutuseless/devoutaudio">Github</a><br/> <a href="http://coolbutuseless.github.io/package/devoutaudio">Online documentation</a> |
| <img src="man/figures/logodevoutsvg.png"><br/> SVG graphics device with pattern support <br/><a href="http://github.com/coolbutuseless/devoutsvg">Github</a><br/> <a href="http://coolbutuseless.github.io/package/devoutsvg">Online documentation</a> |                                                                                                                                                                                                                         |                                                                                                                                                                                                                                                     |

## Helpers for `devoutsvg`

The following packages provide SVG support for use with `minisvg` and
`devoutsvg`

|                                                                                                                                                                                                                                                       |                                                                                                                                                                                                                                           |                                                                                                                                                                                                                              |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="man/figures/logosvgpatternsimple.svg"><br/> Simple SVG patterns<br/><a href="http://github.com/coolbutuseless/svgpatternsimple">Github</a><br/> <a href="http://coolbutuseless.github.io/package/svgpatternsimple">Online documentation</a> | <img src="man/figures/logosvgpatternusgs.svg"> <br/>USGS Patterns<br/><a href="http://github.com/coolbutuseless/svgpatternusgs">Github</a><br/> <a href="http://coolbutuseless.github.io/package/svgpatternusgs">Online documentation</a> | <img src="man/figures/logosvganim.svg"><br/> SVG animation helpers<br/><a href="http://github.com/coolbutuseless/svganim">Github</a><br/> <a href="http://coolbutuseless.github.io/package/svganim">Online documentation</a> |
| <img src="man/figures/logosvgfilter.svg"><br/> SVG filters <br/><a href="http://github.com/coolbutuseless/svgfilter">Github</a><br/> <a href="http://coolbutuseless.github.io/package/svgfilter">Online documentation</a>                             |                                                                                                                                                                                                                                           |                                                                                                                                                                                                                              |

## Want to build your own device?

Best starting point is to read the [vignettes for the `devout`
package](https://coolbutuseless.github.io/package/devout/articles/creating-an-svg-device-01.html)
which steps through the process of building a simple SVG graphics output
device.
