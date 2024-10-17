# helloworld
# helloworld
# helloWorld
helloWorld package was created to exemplify GitHub and R Studio Integration.
### Note

To install a GitHub Pakage in R you may need *devtools*. If so, please run the following code:
```R
if (!requireNamespace("devtools", quietly = TRUE))
 install.packages("devtools")
```
You can install an R package that is publicly available in GitHub by using the following code
(replacing **GitHubName/repo** with the correct information):
```R
devtools::install_github('GitHubName/repo')
```
