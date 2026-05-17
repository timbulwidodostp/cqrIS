# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fit Censored Quantile Regression with Induced Smoothing
res Use cqrIS With (In) R Software
install.packages("remotes")
remotes::install_github("ZexiCAI/cqrIS")
library("cqrIS")
# Estimate Fit Censored Quantile Regression with Induced Smoothing
res Use cqrIS With (In) R Software
cqrIS = read.csv("https://raw.githubusercontent.com/timbulwidodostp/cqrIS/main/cqrIS/cqrIS.csv",sep = ";")
cqrIS <- cqrIS(Z = as.matrix(cqrIS[, -c(1:2)]), X = as.numeric(cqrIS[, 1]), cen = as.numeric(cqrIS[, 2]))
cqrIS
# Fit Censored Quantile Regression with Induced Smoothing
res Use cqrIS With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished