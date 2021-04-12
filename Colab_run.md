### Running the model in Google Colab

Initialize a Colab instance with the R runtime at https://colab.to/r

These are the libraries and packages required to work with the GEM in Google Colab:

```{r}
system(command = "sudo apt-get update -y")
system(command = "sudo apt-get install -y libglpk-dev")
install.packages("glpkAPI")
install.packages("sybil")
```
