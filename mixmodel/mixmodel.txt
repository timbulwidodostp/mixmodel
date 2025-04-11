# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Estimation and Inference in Two-component Mixture Models Use mix.model (mixmodel) With (In) R Software
install.packages("remotes")
remotes::install_github("rohitpatra/mixmodel")
library("mixmodel")
mixmodel = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mixmodel/main/mixmodel/mixmodel.csv",sep = ";")
# Estimation and Inference in Two-component Mixture Models Use mix.model (mixmodel) With (In) R Software
example.vector <- c(mixmodel$x)
mixmodel <- example.vector
mixmodel <- mix.model(mixmodel, method = "cv", gridsize = 600)
print(mixmodel)
# Estimation and Inference in Two-component Mixture Models Use mix.model (mixmodel) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished