Learning GitHub actions
-----------------------

In my attempt to lear github actions here are some of the resources so
far I have come across.

-   [doc.github.com](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#viewing-the-jobs-activity) -
    Understanding GitHub Actions

-   [The
    Distillery](https://distillery.rbind.io/posts/2021-03-18-use-github-actions-with-r-markdown-and-distill/) -
    Use GitHub actions with R Markdown and Distill

-   [Travis Gerke
    presentation](https://tgerke.github.io/github-actions-with-r/#1)

------------------------------------------------------------------------

### Testing

2021-09-24 13:32:14

    dat=rnorm(100)

    plot(dat)

![](README_files/figure-markdown_strict/unnamed-chunk-1-1.png)

------------------------------------------------------------------------

So far `.github/workflow/test_readme.yaml` works to render this readme
on push
