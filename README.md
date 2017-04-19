This is a test for learning R package developing.
`helloToSomeone` package provides only one function `helloTo("NAME")`

  library(devtools)
  install_github('Rokko-Class/package-develop')
  library(helloToSomeone)
  helloTo("YourName")
  [1] "Hello  YourName !"
