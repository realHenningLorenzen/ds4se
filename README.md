# Data Science for Software Engineering

This repository holds work done by [Yim Register][register-yim] for her [RStudio internship][internship] in 2019.
The goal is to develop course materials to teach basic data analysis to programmers using software engineering problems and data sets.
Some of the questions it will show people how to answer include:

-   How many repositories are there on GitHub?
    -   This can be answered with [some API calls][github-api] or via [GHTorrent][ghtorrent]
-   How many people contribute to the average project?
    -   It isn't feasible to examine every project, and they're constantly changing, so we need to talk about sampling and estimation.
-   How long does the average project last?
    -   And is there a correlation between how long a project has been going on and how many people have contributed to it?
        To answer that, we'll have to talk about what correlation means and how to measure it.
-   Are there differences between projects that use different languages?
    -   What do we mean by "use different languages"? Do we rely on self-identification through repository tagging? Do we look at the files in the project? Do those classifications correlate?
    -   And once we have a way to classify projects, what kinds of statistical tests will tell us if two populations are the same or different?

[ghtorrent]: http://ghtorrent.org/
[github-api]: https://developer.github.com/v3/
[internship]: https://blog.rstudio.com/2019/03/25/summer-interns-2019/
[register-yim]: http://students.washington.edu/yreg/
