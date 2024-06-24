# test_deck
flashr test flash card deck for function tutorial
install.packages("flashr")
library(flashr)
r_functions <- c("filter()","select()")
create_deck(x=r_functions, title = "Dplyr Functions")
