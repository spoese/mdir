#' The ggplot theme used for UMD
#'
#' `theme_umd()` uses a theme based on `theme_fivethirtyeight()` from the
#' `ggthemes` package.
#' @examples
#' ggplot(data = mtcars, aes(x = wt, y = mpg, color = factor(cyl))) + geom_point() + theme_mc()
#'
#' @export
theme_umd <- function() {
        theme_fivethirtyeight() +
                theme(legend.position = "none",
                      panel.grid.major.y = element_blank())
}

#' Use UMD's colors for a fill aesthetic
#'
#' `scale_fill_umd()` uses the main colors for the University as a fill option
#' for a categorical data set.
#'
#' @examples
#' ggplot(data = mtcars, aes(x = cyl, fill = factor(cyl))) + geom_histogram() + scale_fill_mc()
#' @export
scale_fill_umd <- function() {
        scale_fill_manual(values = c("#FF0000","#000000","#FFD700","#51237f",
                                     "9FA1A4","#666666","6E4D94","#FF5E3A",
                                     "0E8AD9"))
}

#' Use UMD's colors for a color aesthetic
#'
#' `scale_color_umd()` uses the main colors for the University as a color option for
#' a categorical data set.
#'
#' @examples
#' ggplot(data = mtcars, aes(x = wt, y = mpg, color = factor(cyl))) + geom_point() + scale_color_mc()
#' @export
scale_color_umd <- function() {
        scale_color_manual(values = c("#FF0000","#000000","#FFD700","#51237f",
                                      "9FA1A4","#666666","6E4D94","#FF5E3A",
                                      "0E8AD9"))
}
